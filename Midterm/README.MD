   using System;

    namespace ConsoleApp3
    {
        class Program
        {
            static void Main(string[] args)
            {
                /*int question3 = 2;
                while (question3 > 1)
                {
                    Console.WriteLine("INFINITE LOOP");
                    question3 = question3 + 1;
                }*/
                double question4 = 0;
                int base2 = 2;
                int power = 1;

                while (question4 < 128)
                {
                    question4 = Math.Pow(base2, power);
                    Console.WriteLine($"[{question4}]");
                    power = power + 1;
                }
                int question5 = 49;
                while (question5 >= 1)
                {
                    Console.Write($"{question5},");
                    question5 = question5 - 1;

                }
                Console.WriteLine("   ");
                Console.WriteLine("-------------------------------------------");

                int question6 = 1;
                while (question6 < 22)
                {
                    if (question6 % 2 != 0)
                    {

                        Console.Write($"{question6} ");

                    }
                    question6++;
                }
                bool icerain = false;
                bool tornadowarning = false;
                if(icerain = false)
                {
                    if(tornadowarning = false)
                    {
                        Console.WriteLine("Lets Go Outside!");
                    }
                }

            }
        }
    }
    //Question 1: The three kind of control variables we have are if, for, and while
    //Question 7: the output for the first one would only be *, as the function would run once.
    // if it was a while statement, it would have no output.

