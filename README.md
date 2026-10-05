Практическая работа №2
Выполнил студент группы П25-2.1. Есин Данила Сергеевич
Раздел 3. Операторы языка C#
---
Задача: Вычислите результат выражения int x = 17 / 5; int y = 17 % 5;. Ответ: x = 3, y = 2.

<picture> <img src="3.1/1.png"> 
</picture>


using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp1
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int x = 17 / 5;
            int y = 17 % 5;

            Console.WriteLine($"X = {x}");
            Console.WriteLine($"Y = {y}");

            }
        }
    }
}