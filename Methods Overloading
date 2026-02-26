using System;
using System.Collections.Generic;
using System.Linq;
using System.Security.Cryptography;
using System.Text;
using System.Threading.Tasks;

namespace Method_overloading
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Demo d1 = new Demo();
            d1.Promote(1000, " Amman-Istanbual -Amman", " Kampenski 3days/2night");

            var numbers = new int[] { 1, 2, 3, 4, 5, 6, 7, 8, 9, 10 };
            Demo.PrintEvent(numbers);



        }
    }

    public class Demo
    {
        //Methods overloding 

        public void Promote(double amount)
        {
            Console.WriteLine($"you 've got a promot of {amount}");
        }
        public void Promote(double amount, string trip)
        {
            Console.WriteLine($"you 've got a promot of {amount} and  a trip {trip}");
        }
        public void Promote(double amount, string trip, string hotel)
        {
            Console.WriteLine($"you 've got a promot of {amount} and  a trip {trip} with {hotel}");
        }


        //Expression methods
        // public void Show() => Console.WriteLine("Welcome to our promotion");
        // Static method
        //public static void ShowStatic() => Console.WriteLine("Welcome to our promotion");

        // Local function
        public static void PrintEvent(int[] original)
        {
            foreach (var item in original)
            {
                if (item % 2 == 0)
                {
                    Console.WriteLine(item + " ");

                }
            }
            bool IsEven(int number) => number % 2 == 0; // Local function, equivalent to:
                                                        // bool IsEven(int number)
                                                        // { if (number % 2 == 0)
                                                        //{
                                                        //     return true ;
                                                        // else
                                                        //{
                                                        //return false;
                                                        //}
        }

    }

}

     

  

    
