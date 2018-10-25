using System;

namespace ConsoleApp1
{
    class Program
    {
        static void Main(string[] args)
        {
            var kitty = new HouseCat();
            kitty.Eat();
            Console.WriteLine(kitty.HowManyCat());
            Console.ReadLine();
        }
    }

    class Feline
    {
        private static int howManyCats = 0; 

        public Feline()
        {
            howManyCats++;
        }

        public void Eat()
        {
            Console.WriteLine("In Feline Eat Method!");
        }

        public int HowManyCat()
        {
            return howManyCats;
        } 
    }
    
    class HouseCat : Feline
    {
        public HouseCat()
        {            
            Console.WriteLine("In House Cat Method");
        }
    }
}
