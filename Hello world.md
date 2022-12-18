``` C#
using System;
class HelloWorld {
  static void Main() {
    Console.WriteLine("Введите первое число: ");
    int number_1=Convert.ToInt32(Console.ReadLine());
    Console.WriteLine("Введите второе число: ");
    int number_2=Convert.ToInt32(Console.ReadLine());
    if (number_2!=number_1)
    {
        if (number_2>number_1)
    {
        Console.Write($"Наибольшее число это {number_2}");   
    }
        else
    {
        Console.Write($"Наибольшее числ это ({number_1})");
    }
    }
    else
    {
        Console.Write($"Два числа равны между собой({number_1})");
    }
  }
}

```