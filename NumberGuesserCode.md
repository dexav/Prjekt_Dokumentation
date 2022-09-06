using System;

namespace NumverguesserV2
{
    internal class Program
    {
        static void Main(string[] args)
        {
            
            
            Console.BackgroundColor = ConsoleColor.Black;
            Console.ForegroundColor = ConsoleColor.Cyan;
            Console.WriteLine("----------------------------------------------Wilkommen zu NumberGuesser!----------------------------------------------");
            Console.WriteLine("Das Ziel ist die richtige Zahl zu erraten. Viel Spass!");


            string nochmal = "n";
            do
            {
               
                Random random = new Random();

                int RNumber = random.Next(0, 100);

                int Guess = 0;
                Console.ForegroundColor = ConsoleColor.White;
                Console.WriteLine("Gib hier eine Zahl zwischen 1-100 ein:");


                try
                {

                    while (Guess != RNumber)
                    {
                        Console.ForegroundColor = ConsoleColor.White;
                        Guess = Convert.ToInt32(Console.ReadLine());
                        if (Guess > 100)
                        {
                            throw new Exception();
                        }
                        if (Guess < 0)
                        {

                            throw new Exception();
                        }
                        if (Guess < RNumber)
                        {
                            Console.ForegroundColor = ConsoleColor.Red;
                            Console.WriteLine("Deine Nummer ist zu klein. Versuchs nochmal:");

                        }
                        else if (Guess > RNumber)
                        {
                            Console.ForegroundColor = ConsoleColor.Red;
                            Console.WriteLine("Deine Nummer ist zu gross. Versuchs nochmal:");

                        }
                        else if (Guess == RNumber)
                        {


                            Console.ForegroundColor = ConsoleColor.Green;
                            Console.WriteLine("Glückwunsch, du hast es richtig erraten!");
                            Console.ReadLine();
                            Console.WriteLine("Willst du nochmals spielen? [y/n]");
                            nochmal = Console.ReadLine();

                        }



                    }
                }
                catch
                {
                    Console.WriteLine("So funktioniert das nicht");
                }
                
            } while (nochmal == "y");




          





        }
    }
}
