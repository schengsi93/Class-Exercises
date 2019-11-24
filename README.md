# Class-Exercises



using System;

namespace Day1Exercises
{
    class Class1
    {
        static void Main(string[] args)
        {
            //this is section B
            Console.Write("Please enter a number: ");
            double value = Convert.ToDouble(Console.ReadLine());
            Console.WriteLine(Math.Sqrt(value));

            Console.Write("Please enter a number: ");
            double value2 = Convert.ToDouble(Console.ReadLine());
            Console.WriteLine($"{Math.Sqrt(value2):0.000}");
            //as the question got say round, should use the math round function, round to 3 dp

            Console.Write("Please enter your salary: ");
            int value3 = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine($"{value3 * 1.13:C}");

            Console.Write("Temperature in Centigrade: ");
            int value4 = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Temperature in Fahrenheit: "+ $"{value4 * 1.8 + 32}");

            Console.Write("Value of x: ");
            int value5 = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Value of y: " + $"{5 * value5 * value5 - 4 * value5 + 3}");

            Console.Write("Value of x1: ");
            int x1 = Convert.ToInt32(Console.ReadLine());
            Console.Write("Value of x2: ");
            int x2 = Convert.ToInt32(Console.ReadLine());
            Console.Write("Value of y1: ");
            int y1 = Convert.ToInt32(Console.ReadLine());
            Console.Write("Value of y2: ");
            int y2 = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Distance = " + $"{Math.Sqrt((x2-x1)*(x2-x1)+(y2-y1)*(y2-y1))}");
            //inside math sqrt (Math.Pow(x2-x1,2)+Math.Pow(y2-y1,2)

            Console.Write("Distance travelled: ");
            double dist = Convert.ToDouble(Console.ReadLine());
            Console.WriteLine("Total fare = " +$"{2.4 + dist * 0.4}");

            Console.Write("Distance travelled: ");
            double dist2 = Convert.ToDouble(Console.ReadLine());
            Console.WriteLine("Total fare = " + $"{Math.Round(2.4 + dist2 * 0.4,1):0.00}");

            Console.Write("Distance travelled: ");
            double dist3 = Convert.ToDouble(Console.ReadLine());
            Console.WriteLine("Total fare = " + $"{Math.Ceiling((2.4 + dist3 * 0.4)*10)/10:0.0}");

            Console.Write("a: ");
            int a = Convert.ToInt32(Console.ReadLine());
            Console.Write("b: ");
            int b = Convert.ToInt32(Console.ReadLine());
            Console.Write("c: ");
            int c = Convert.ToInt32(Console.ReadLine());
            int s = (a + b + c) / 2;
            Console.WriteLine("Area = " + $"{Math.Sqrt(s*((s-a)*(s-b)*(s-c)))}");
        }
    }
}
