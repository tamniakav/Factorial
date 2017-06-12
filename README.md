using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Factorial
{
    class Factorial
    {
        static void Main(string[] args)
        {
            int n = int.Parse(Console.ReadLine());

            int num = 1;
            int a = 1;

            for (int i = 1; i <= n; i++)
            {
                num = a * i;
                a = num;
            }
            Console.WriteLine(a);
        }
    }
}
