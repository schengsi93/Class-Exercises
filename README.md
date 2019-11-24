# Class-Exercises

Write a program that takes a double precision number as input and prints the square root of the number.
            
            Console.Write("Please enter a number: ");
            double value = Convert.ToDouble(Console.ReadLine());
            Console.WriteLine(Math.Sqrt(value));

Write a program that takes a double precision number as input and prints the square root of the number.
The square root should be rounded to 3 decimal places.
            
            Console.Write("Please enter a number: ");
            double value2 = Convert.ToDouble(Console.ReadLine());
            Console.WriteLine($"{Math.Sqrt(value2):0.000}");

The ABC Company pays its employees salary plus benefits. The benefits are calculated as a percentage of the salary.
The company pays every employee 10% housing allowance and 3% transport allowance.
Write a program that takes the salary as input and prints the total income
(salary + housing allowance + transport allowance) as output. Format the output in currency format.
            
            Console.Write("Please enter your salary: ");
            int value3 = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine($"{value3 * 1.13:C}");

Write a program that would convert temperature given in Centigrade scale to Fahrenheit – the number can be integer or real. To convert temperature in Centigrade (C) to Fahrenheit (F) use the formula: F = 1.8 * C + 32          
            
            Console.Write("Temperature in Centigrade: ");
            int value4 = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Temperature in Fahrenheit: "+ $"{value4 * 1.8 + 32}");

Write a program that would take as input the value of x and calculate & output the value of y using the formula: y = 5 x2 – 4 x + 3

            Console.Write("Value of x: ");
            int value5 = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Value of y: " + $"{5 * value5 * value5 - 4 * value5 + 3}");

Write a program that reads the (x, y) coordinates of two points. Compute the distance between the two points using the formula:
Distance = Square Root of [( x2 – x1 )^2 + ( y2 – y1 )^2 ]

Note: A common question that arises is that how to get four inputs (two pairs of x and y) from the users all at once. At this moment, we haven’t learned about string manipulation and therefore you should just ask for user input four times.

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

ABC Taxi Company has the following meter charges based on the kilometres travelled.
Minimum fixed charge: $2.40 In addition the fare would be computed at 40 cents per kilometer.

            Console.Write("Distance travelled: ");
            double dist = Convert.ToDouble(Console.ReadLine());
            Console.WriteLine("Total fare = " +$"{2.4 + dist * 0.4}");

In the ABC Taxi Company problem above, print the output so that the fare is the output is printed always rounded to nearest 10 cents and printed to two decimal places.

            Console.Write("Distance travelled: ");
            double dist2 = Convert.ToDouble(Console.ReadLine());
            Console.WriteLine("Total fare = " + $"{Math.Round(2.4 + dist2 * 0.4,1):0.00}");

In the ABC Taxi Company problem above, calculate the fare so that the fare is always rounded upwards to the nearest 10 cents.

            Console.Write("Distance travelled: ");
            double dist3 = Convert.ToDouble(Console.ReadLine());
            Console.WriteLine("Total fare = " + $"{Math.Ceiling((2.4 + dist3 * 0.4)*10)/10:0.0}");
