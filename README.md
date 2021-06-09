# CalculatorByChintu
Source Code - 
using System;

namespace CALCULKATOR
{
	class Program
	{
		static void Main(string[] args)
		{
			Console.WriteLine(".................");
			Console.WriteLine("Check1 - PASSED");
			System.Threading.Thread.Sleep(1000);
			Console.WriteLine("Check2 - PASSED");
			System.Threading.Thread.Sleep(1000);
			Console.WriteLine("Check3 - PASSED");
			System.Threading.Thread.Sleep(1000);
			Console.WriteLine("Check4 - PASSED");
			System.Threading.Thread.Sleep(1000);
			Console.WriteLine("Check5 - PASSED");
			System.Threading.Thread.Sleep(1000);
			Console.WriteLine("Check6 - PASSED");
			System.Threading.Thread.Sleep(1000);
			Console.WriteLine(".................");
			Console.WriteLine("all checks passed, continuing the execution");
			System.Threading.Thread.Sleep(2300);
			Console.WriteLine("1%");
			System.Threading.Thread.Sleep(2300);
			Console.WriteLine("100%");
			System.Threading.Thread.Sleep(2300);
			Console.WriteLine("Loaded everything! Started Program");

			Console.Write("Enter a Number: ");
			double num1 = Convert.ToDouble(Console.ReadLine());

			Console.Write("Enter A operator: ");
			string op = Console.ReadLine();


			// second number input from the user
			Console.Write("Enter a Number: ");
			double num2 = Convert.ToDouble(Console.ReadLine());

			// if statement for the calculator to work.
			if(op == "+")
			{
				Console.WriteLine(num1 + num2);
			} else if (op == "-")
			{
				Console.WriteLine(num1 - num2);
			} else if (op == "*")
			{
				Console.WriteLine(num1 * num2);
			} else if(op == "/")
			{
				Console.WriteLine(num1 / num2);
			} else
			{
				Console.WriteLine("The Specified operator: " + op + " is not recognised, please read our Github For Why this operator is not valid.");
			}
			Console.WriteLine("Program is cleaning before it closes!");
			System.Threading.Thread.Sleep(1000);
			Console.WriteLine("1% ///");
			System.Threading.Thread.Sleep(1000);
			Console.WriteLine("2% ////");
			System.Threading.Thread.Sleep(1000);
			Console.WriteLine("3% /////");
			System.Threading.Thread.Sleep(1000);
			Console.WriteLine("80% ///////////////////////////////////////////////////////////////////////////////////////////////");
			System.Threading.Thread.Sleep(1000);
			Console.WriteLine("100% /////////////////////////////////////////////////////////////////////////////////////////////////////////////////");
			System.Threading.Thread.Sleep(1000);
			Console.WriteLine("Quitting...");
			System.Threading.Thread.Sleep(3000);
			Environment.Exit(0);
			
		}
	}
}
