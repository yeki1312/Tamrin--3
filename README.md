# Tamrin--3using System;

class Program
{
    static void Main()
    {
        // رسم حرف E
        Console.WriteLine("حرف E:");
        for (int i = 0; i < 7; i++)
        {
            if (i == 0 || i == 3 || i == 6)
                Console.WriteLine("*******");
            else
                Console.WriteLine("*");
        }

        Console.WriteLine();

        // رسم حرف H
        Console.WriteLine("حرف H:");
        for (int i = 0; i < 7; i++)
        {
            if (i == 3)
                Console.WriteLine("*     *");
            else
                Console.WriteLine("*     *");
        }

        Console.WriteLine();

        // رسم حرف L
        Console.WriteLine("حرف L:");
        for (int i = 0; i < 6; i++)
        {
            Console.WriteLine("*");
        }
        Console.WriteLine("*******");
    }
}

