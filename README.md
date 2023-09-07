// задайте значения M и N. Напишите программу, которая 
// //выведет все натуральные числа в промежутке от M до N.
// //M = 1; N = 5 -> "1, 2, 3, 4, 5"
// //M = 4; N = 8 -> "4, 6, 7, 8"


// int ReadInt(string argument) 
// {
//     Console.Write(argument);
//     int i;
//     while (!int.TryParse(Console.ReadLine(), out i))
//     {
//         System.Console.WriteLine("Это не число!");
//         Console.Write(argument);
//     }
//     return i;
// }
// string NumbersRec1(int m, int n)
// {
//     if (m < n + 1) return $"{m} " + NumbersRec1(m + 1, n);
//     else return String.Empty;
// }
// int m = ReadInt("Введите M: ");
// int n = ReadInt("Введите N: ");
// System.Console.WriteLine(NumbersRec1(m, n));

// Задайте значения M и N. Напишите программу, 
// //которая найдёт сумму натуральных элементов в промежутке от M до N.
// //M = 1; N = 15 -> 120
// //M = 4; N = 8. -> 30

// int ReadInt(string argument) 
// {
//     Console.Write(argument);
//     int i;
//     while (!int.TryParse(Console.ReadLine(), out i))
//     {
//         System.Console.WriteLine("Это не число!");
//         Console.Write(argument);
//     }
//     return i;
// }
// int SumNumbers(int m, int n)
// {
//     if (n == m) return n;
//     else return n + SumNumbers(m, n - 1);
// }
// int m = ReadInt("Введите M: ");
// int n = ReadInt("Введите N: ");
// if (n < m)
// {
//     int temp = n;
//     n = m;
//     m = temp;
// }
// System.Console.WriteLine(SumNumbers(m, n));

// Напишите программу вычисления функции Аккермана с помощью рекурсии. 
// //Даны два неотрицательных числа m и n.
// //m = 2, n = 3 -> A(m,n) = 29



// //Кажется в примере ошибка, надо так : m = 3, n = 2 -> A(m,n) = 29
// int ReadInt(string argument) 
// {
//     Console.Write(argument);
//     int i;
//     while (!int.TryParse(Console.ReadLine(), out i))
//     {
//         System.Console.WriteLine("Это не число!");
//         Console.Write(argument);
//     }
//     return i;
// }
// int Akkerman(int m, int n)
// {
//     if (m == 0) return n + 1;
//     else if (n == 0) return Akkerman(m - 1, 1);
//     else return Akkerman(m - 1, Akkerman(m, n - 1));
// }

// int m = ReadInt("Введите M: ");
// int n = ReadInt("Введите N: ");
// System.Console.WriteLine(Akkerman(m, n));
