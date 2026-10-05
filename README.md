Практическая работа №3. Управляющие конструкции и операторы ветвления в C# (if, else if, else, switch).

№1
<img width="1919" height="1007" alt="image" src="https://github.com/user-attachments/assets/d3acf39a-2b9b-48c9-8e30-9ea164fe1cc7" />
Console.WriteLine("Введите целое число: ");

int a1 = int.Parse(Console.ReadLine());

if (a1 >= 1)
{
    Console.WriteLine("Число положительное.");
}

else
{
    Console.WriteLine("Число отрицательное.");
}
break;

№2
<img width="1919" height="1007" alt="image" src="https://github.com/user-attachments/assets/dbd2da38-38e4-4adc-a0ef-949b8fa798e0" />
Console.WriteLine("Введите целое число: ");

int a2 = int.Parse(Console.ReadLine());

if (a2 % 2 == 0)
{
    Console.WriteLine("Число чётное.");
}

else
{
    Console.WriteLine("Число нечётное.");
}
break;

№3
<img width="1919" height="1007" alt="image" src="https://github.com/user-attachments/assets/7e92fd5f-c4b0-44e0-a5aa-6bcb0d6b55b6" />
Console.WriteLine("Введите 2 целых числа: ");

int a3 = int.Parse(Console.ReadLine());
int b3 = int.Parse(Console.ReadLine());

if (a3 == b3)
{
    Console.WriteLine("Числа равны.");
}
else if (a3 > b3)
{
    Console.WriteLine("1 число больше 2.");
}
else
{
    Console.WriteLine("2 число больше 1.");
}
break;

№4
<img width="1919" height="1004" alt="image" src="https://github.com/user-attachments/assets/2ceb556f-0502-43b7-96f7-eaa8c9f3b7f5" />
Console.WriteLine("Введите 2 числа с плавающей точкой: ");

double a4 = double.Parse(Console.ReadLine());
double b4 = double.Parse(Console.ReadLine());

if (a4 == b4)
{
    Console.WriteLine("Числа равны.");
}
else if (a4 > b4)
{
    Console.WriteLine($"Наименьшее число - {b4}.");
}
else
{
    Console.WriteLine($"Наименьшее число - {a4}.");
}
break;

№5
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2ab72541-4a6a-42e0-9f60-9997546df49f" />
Console.WriteLine("Введите число: ");

double a5 = double.Parse(Console.ReadLine());

if (a5 % 5 == 0)
{
    Console.WriteLine("Число делится нацело на 5.");
}

else
{
    Console.WriteLine("Число не делится нацело на 5.");
}
break;

№6


        
Console.WriteLine("Введите число: ");

double a6 = double.Parse(Console.ReadLine());

if (a6 % 10 == 0)
{
    Console.WriteLine("Число оканчивается на 0.");
}

else
{
    Console.WriteLine("Число не оканчивается 0.");
}
break;





