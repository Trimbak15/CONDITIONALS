# CONDITIONALS
Notes &amp; some sums related conditionals 

$ Data-Structures $
1.Integer - it consist about an value i.e - 1-100

2.Float - decimal number

3.Double - large decimal number

4.Long - long number such as mobile number

5.Character - single character i.e 'A'

6.String - a whole string like a full name of someone

7.Boolean - consist only two value true/false

$ OPERATORS $
1. " = " - assignment operator (used to put the value in the variable)
2. " == " - comparison operator (used to compare the two number or anything)

$ LOGICAL OPERATOR $

1.AND (&&) - check if the number is inside this or not

2.OR (||) - it will notify us that the number is present here

3.NOT (!=) - it convey that the value is not equal to something

*** SOME CODING EXAMPLES ***

1. Leap year or not
import java.util.*;
import java.lang.*;
import java.io.*;

public class Main
{
	public static void main (String[] args) throws java.lang.Exception
	{
  Scanner sc = new Scanner(System.in);
		int year = sc.nextInt();
   if((year%400==0) || ((year%4==0) && (year%100!=0)))
   {
     System.out.println(1);
   }
    else
    {
      System.out.println(0);
    }
  }
}

2. Big light (medium level)

import java.util.*;
import java.lang.*;
import java.io.*;

public class Main
{
	public static void main (String[] args) throws java.lang.Exception
	{
		//your code here
        Scanner in = new Scanner(System.in);
        int h1 = in.nextInt();
		int h2 = in.nextInt();
		int v1 = in.nextInt();
		int v2 = in.nextInt();
		
		if(v1!=v2)
		{
		    if((h2-h1)%(v1-v2) == 0)
		    {
		        // time is integer 
		        System.out.println("true");
		    }
		    else
		    {
		        System.out.println("false");
		    }
		}
		else 
		{
		    System.out.println("false");
		}
	}

}
