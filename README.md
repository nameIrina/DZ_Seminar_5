//# DZ_Seminar_5
// Задайте массив заполненный случайными положительными трёхзначными числами. Напишите программу, которая покажет количество чётных чисел в массиве.
//[345, 897, 568, 234] -> 2

//  int[] array = new int[4];
//  int countPol = 0;
//  for (int i = 0; i < array.Length; i++)
//  {
//      array[i] = new Random().Next(100, 999);
//      Console.Write(array[i] + " ");
//      if (array[i] % 2 == 0) countPol = countPol + 1;
//  }
//  Console.Write("Количество чётных чисел в массиве: " + countPol);

// Задача 36: Задайте одномерный массив, заполненный случайными числами. Найдите сумму элементов, стоящих на нечётных позициях.
// [3, 7, 23, 12] -> 19
// [-4, -6, 89, 6] -> 0

//   int[] array = new int[7];
//   int arraySize = array.Length; 
//   int sumNumber = 0;
// for (int j = 0; j < arraySize; j++)
//  {
//      array[j] = new Random().Next(10);
//  }
//  Console.WriteLine($"array: [ {String.Join(" ;", array)} ]");
//     for (int i = 0; i < arraySize; i++)
//     {
//       Console.Write(array[i] + " ");
//       if (i % 2 != 0) sumNumber = sumNumber + array[i];
//     }
// Console.WriteLine($"Сумма элементов, стоящих на нечётных позициях: {sumNumber}");

// Задача 38: Задайте массив вещественных чисел. Найдите разницу между максимальным и минимальным элементов массива.
// [3 7 22 2 78] -> 76

// double[] array = new double[10];
//   for (int j = 0; j < array.Length; j++)
//   {
//     array[j] = new Random().Next(1, 20);
//     Console.Write(array[j] + " ");
//   }
// double maxNumber = array[0];
// double minNumber = array[0];
//   for (int i = 1; i < array.Length; i++)
//   {
//     if (maxNumber < array[i]) maxNumber = array[i];
//     if (minNumber > array[i]) minNumber = array[i];
//   }    
//   double decision = maxNumber - minNumber;
//   Console.WriteLine($"Разница между между максимальным ({maxNumber}) и минимальным({minNumber}) элементами: {decision}");
