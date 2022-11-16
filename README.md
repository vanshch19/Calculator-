# Calculator-

import java.lang.*;
import java.util.*;

public class Calculator{
	
	//Function for Addition
	public static int Add(int x,int y)
	{
		int a = x + y;
		return a;	
	}
	
	//Function for Subtraction
	public static int Sub(int x, int y)
	{
		int s = x - y;
		return s;
	}

	
	//Function for Division
	public static int Div(int x, int y)
	{
		int d = x/y;
		return d;
	}

	
	//Function for Multiplication
	public static int Mul(int x, int y)
	{
		int p = x*y;
		return p;
	}

	
	//Function for Square Root
	public static double Sqrt(int x)
	{
		double sqrt = Math.sqrt(x);
		return sqrt;
	}


	//Function for Square
	public static int Square(int x)
	{
		int sqr = x*x;
		return sqr;
	}


	//Function for Logarithmic
	public static double Log(int x)
	{
		double l = Math.log(x);
		return l;
	}
	

	//Function for Modulas
	public static int Mod(int x, int y)
	{
		int m = x % y;
		return m;
	}
	

	//Function for Percentage
	public static double Per(int x, int y, int z, int u, int s)
	{
		double per = ((x + y + z + u + s)*100) / 500;
		return per;
	}
	

	//Function for Power
	public static double Pow(int x, int y)
	{
		double pow = Math.pow(x, y);
		return pow;
	}
	
	
	public static void main(String args[])
	{
		Scanner scn = new Scanner(System.in);	


		System.out.println("Hello welcome !!");
		System.out.println("options are :");
		System.out.println("1. ADDITION");
		System.out.println("2. SUBTRACTION");
		System.out.println("3. DIVISION");
		System.out.println("4. MULTIPLICATION");
		System.out.println("5. SQUARE ROOT");
		System.out.println("6. SQUARE");
		System.out.println("7. LOG");
		System.out.println("8. MOD");
		System.out.println("9. PERCENTAGE");
		System.out.println("10. POWER");

			

		System.out.println("Enter the option");
		int options = scn.nextInt();
		
		while(true)
		{
			if(options == 1)
			{ 
				System.out.println("You choosed Addition !!!");
				System.out.println("Enter the Values ");
				int value1 = scn.nextInt();
				int value2 = scn.nextInt();
				int result = Add(value1, value2);	
				System.out.println("Result is : " + result);				
			}
			
			else if(options == 2)
			{
				System.out.println("You choosed Subtraction !!");
				System.out.println("Enter the Values ");
				int value1 = scn.nextInt();
				int value2 = scn.nextInt();
				int result = Sub(value1, value2);
				System.out.println("Result is : " + result);
			}

			else if(options == 3)
			{
				System.out.println("You choosed Division !!");
				System.out.println("Enter the Values ");
				int value1 = scn.nextInt();
				int value2 = scn.nextInt();
				int result = Div(value1, value2);	
				System.out.println("Result is : " + result);
			}

			else if(options == 4)
			{
				System.out.println("You choosed Multiplication !!");
				System.out.println("Enter the Values ");
				int value1 = scn.nextInt();
				int value2 = scn.nextInt();
				int result = Mul(value1, value2);	
				System.out.println("Result is : " + result);
			}

			else if(options == 5)
			{
				System.out.println("You choosed Square Root !!");
				System.out.println("Enter the Value ");
				int value1 = scn.nextInt();
				double result = Sqrt(value1);	
				System.out.println("Result is : " + result);
			}
	
			else if(options == 6)
			{
				System.out.println("You choosed Square !!");
				System.out.println("Enter the Value ");
				int value1 = scn.nextInt();
				int result = Square(value1);	
				System.out.println("Result is : " + result);
			}

			else if(options == 7)
			{
				System.out.println("You choosed Log !!");
				System.out.println("Enter the Value ");
				int value1 = scn.nextInt();
				double result = Log(value1);	
				System.out.println("Result is : " + result);
			}

			else if(options == 8)
			{
				System.out.println("You choosed Modulas !!");
				System.out.println("Enter the Values ");
				int value1 = scn.nextInt();
				int value2 = scn.nextInt();
				int result = Mod(value1, value2);	
				System.out.println("Result is : " + result);
			}
		
			else if(options == 9)
			{
				System.out.println("You choosed Percentage !!");
				System.out.println("Enter the five Values ");
				int value1 = scn.nextInt();
				int value2 = scn.nextInt();
				int value3 = scn.nextInt();
				int value4 = scn.nextInt();
				int value5 = scn.nextInt();
				double result = Per(value1, value2, value3, value4, value5);	
				System.out.println("Result is : " + result);
			}

			else if(options == 10)
			{
				System.out.println("You choosed Power !!");
				System.out.println("Enter the Values ");
				int value1 = scn.nextInt();
				int value2 = scn.nextInt();
				double result = Pow(value1, value2);	
				System.out.println("Result is : " + result);
			}

		System.out.println("Enter the option");
		options = scn.nextInt();
			
		}
	
	
	}

}
