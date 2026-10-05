<img width="1912" height="1003" alt="image" src="https://github.com/user-attachments/assets/4d3a587c-fff8-4fd2-9265-caa47605212d" />Практическая работа №3. Управляющие конструкции и операторы ветвления в C# (if, else if, else, switch).

Раздел 1. Базовые условия if и if-else

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

№6
<img width="1919" height="1008" alt="image" src="https://github.com/user-attachments/assets/38847c41-cfb9-4f88-9d39-ade8011c13ae" />   
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

№7
<img width="1919" height="1006" alt="image" src="https://github.com/user-attachments/assets/ee7ea1eb-1901-45e1-ae1d-7d507cdea02d" />
Console.WriteLine("Введите температуру воздуха: ");

double a7 = double.Parse(Console.ReadLine());

if (a7 > 0)
{
    Console.WriteLine("Всё норм.");
}

else
{
    Console.WriteLine("На улице мороз, наденьте шапку.");
}

№8
<img width="1903" height="1000" alt="image" src="https://github.com/user-attachments/assets/4dddb2ab-905d-44ea-b5d4-f879d5ce200f" />
Console.WriteLine("Введите число: ");

double a8 = double.Parse(Console.ReadLine());

if (a8 > 100)
{
    Console.WriteLine(a8 - 20);
}

else
{
    Console.WriteLine(a8 + 10);
}

№9
<img width="1919" height="1008" alt="image" src="https://github.com/user-attachments/assets/300bcce1-6656-48b9-ac2b-7dd3131269dc" />
Console.WriteLine("Введите 2 числа: ");

double a9 = double.Parse(Console.ReadLine());
double b9 = double.Parse(Console.ReadLine());

if (a9 == b9)
{
    Console.WriteLine("Числа равны.");
}

else
{
    Console.WriteLine($"Произведение чисел - {a9 * b9}");
}

№10
<img width="1918" height="1007" alt="image" src="https://github.com/user-attachments/assets/6b9b131f-c253-4e14-b79f-c370c68d7a30" />
Console.WriteLine("Введите возраст: ");

double a10 = double.Parse(Console.ReadLine());

if (a10 >= 18)
{
    Console.WriteLine("Доступ разрешён.");
}

else
{
    Console.WriteLine("доступ запрещён.");
}

№11
<img width="1917" height="1007" alt="image" src="https://github.com/user-attachments/assets/a0f5baf4-8df0-491a-aa1d-75641fc0c841" />
Console.WriteLine("Введите число: ");

double a11 = double.Parse(Console.ReadLine());

if (a11 >= 100 && a11 <= 999)
{
    Console.WriteLine("Да.");
}

else
{
    Console.WriteLine("Нет.");
}

№12
<img width="1919" height="1003" alt="image" src="https://github.com/user-attachments/assets/39e2b659-81ee-45b4-a5c0-97806fa2701f" />
Console.WriteLine("Введите число: ");

double a12 = double.Parse(Console.ReadLine());

if (a12 % 3 == 0)
{
    Console.WriteLine("Число делится на 3 без остатка.");
}

else
{
    Console.WriteLine("Число не делится на 3 без остатка.");
}

№13
<img width="1919" height="1004" alt="image" src="https://github.com/user-attachments/assets/fd49fb27-c852-4897-9ec1-5d840f6054fe" />
Console.WriteLine("Введите координаты на оси Х : ");

double a13 = double.Parse(Console.ReadLine());

if (a13 > 0)
{
    Console.WriteLine("Точка правее 0.");
}

else
{
    Console.WriteLine("Точка левее 0 .");
}

№14
<img width="1915" height="1006" alt="image" src="https://github.com/user-attachments/assets/8242b474-6264-4dc3-9053-d334a07ee65b" />
Console.WriteLine("Введите баланс счёта: ");

double a14 = double.Parse(Console.ReadLine());

if (a14 >= 0)
{
    Console.WriteLine("Всё норм.");
}

else
{
    Console.WriteLine("Задолженность!");
}

№15
<img width="1918" height="1004" alt="image" src="https://github.com/user-attachments/assets/1072830a-5094-4f68-9877-2e2dc3727b7d" />
Console.WriteLine("Введите пароль: ");

double a15 = double.Parse(Console.ReadLine());

if (a15 == 1234)
{
    Console.WriteLine("Вход выполнен.");
}

else
{
    Console.WriteLine("Неверный пароль.");
}

№16
<img width="1918" height="1005" alt="image" src="https://github.com/user-attachments/assets/ba48c03b-a2bc-43ba-ad1b-e8c51f233ed9" />
Console.WriteLine("Введите число: ");

double a16 = double.Parse(Console.ReadLine());

if (a16 < 0)
{
    Console.WriteLine("Число отрицательное.");
}

else
{
    Console.WriteLine("Число не отрицательное.");
}

№17
<img width="1919" height="1009" alt="image" src="https://github.com/user-attachments/assets/e492cd27-c7a1-4b7b-823a-59e63de2487a" />
Console.WriteLine("Введите 2 числа: ");

double a17 = double.Parse(Console.ReadLine());
double b17 = double.Parse(Console.ReadLine());

if (a17 > b17)
{
    Console.WriteLine($"Разность: {a17 - b17}.");
}

else if (a17 == b17)
{
    Console.WriteLine("Числа равны.");
}

else
{
    Console.WriteLine($"Разность: {b17 - a17}");
}

№18
<img width="1919" height="1008" alt="image" src="https://github.com/user-attachments/assets/6393decc-dc82-4461-8ef1-92fb7cd43fc5" />
Console.WriteLine("Сумму покупки: ");

double a18 = double.Parse(Console.ReadLine());

if (a18 > 1000)
{
    Console.WriteLine($"Итоговая цена - {a18 * 0.95}.");
}

else
{
    Console.WriteLine($"Итоговая цена - {a18}.");
}

№19
<img width="1919" height="1008" alt="image" src="https://github.com/user-attachments/assets/e64a93c8-0c9b-43df-8d57-e367289fafdc" />
Console.WriteLine("Введите целое число: ");

double a19 = double.Parse(Console.ReadLine());

if (a19 % 2 == 0)
{
    Console.WriteLine($"Число чётное: {a19} / 2 = {a19/2}.");
}

else
{
    Console.WriteLine($"Число нечётное: {a19} * 3 = {a19 * 3}.");
}

№20
<img width="1919" height="1007" alt="image" src="https://github.com/user-attachments/assets/cb451631-cf19-4f1c-aca7-a8eb0b0904ae" />
Console.WriteLine("Введите скорость км/ч: ");

int a20 = int.Parse(Console.ReadLine());

if (a20 > 90)
{
    Console.WriteLine("Нарушение правил.");
}

else
{
    Console.WriteLine("Всё хорошо.");
}

№21
<img width="1919" height="1006" alt="image" src="https://github.com/user-attachments/assets/3e499cf4-547b-4346-beee-01e2f0a2e507" />
Console.WriteLine("Введите целое число: ");

double a21 = double.Parse(Console.ReadLine());

if (a21 == 0)
{
    Console.WriteLine("Число равно 0.");
}

else
{
    Console.WriteLine("Число не равно 0.");
}

№22
<img width="1917" height="1007" alt="image" src="https://github.com/user-attachments/assets/eede31ad-dcba-45e8-b832-cc20b0bb5584" />
Console.WriteLine("Введите 2 вещественных числа: ");

double a22 = double.Parse(Console.ReadLine());
double b22 = double.Parse(Console.ReadLine());

if (Math.Abs(a22 - b22) < 0.001)
{
    Console.WriteLine("Числа равны.");
}

else
{
    Console.WriteLine("Числа не равны");
}

#23
<img width="1912" height="1003" alt="image" src="https://github.com/user-attachments/assets/6ea2e2b5-f72a-4329-9fc8-974a49a94a60" />
Console.WriteLine("Введите число $A$ и число $B$: ");

double a23 = double.Parse(Console.ReadLine());
double b23 = double.Parse(Console.ReadLine());

if (a23 % b23 == 0)
{
    Console.WriteLine("Число $A$ делится без остатка на число $B$.");
}

else
{
    Console.WriteLine("Число $A$ не делится без остатка на число $B$.");
}

№24
<img width="1919" height="1000" alt="image" src="https://github.com/user-attachments/assets/297947b8-de59-4781-9e01-d6b2b9c442b6" />
Console.WriteLine("Введите 2 угла треугольника: ");

double a24 = double.Parse(Console.ReadLine());
double b24 = double.Parse(Console.ReadLine());

if (a24 + b24 <= 180)
{
    Console.WriteLine("Треугольник существует.");
}

else
{
    Console.WriteLine("Треугольник не существует.");
}

№25
<img width="1919" height="1002" alt="image" src="https://github.com/user-attachments/assets/666187ff-dc5c-414c-a106-76a78f995b0b" />
Console.Write("Введите радиус круга и сторону квадрата: ");

double a25 = double.Parse(Console.ReadLine());
double b25 = double.Parse(Console.ReadLine());

if(Math.PI * a25 * a25 > b25 * b25)
{
    Console.WriteLine("Площадь круга больше.");
}

else if(Math.PI * a25 * b25 < a25 * b25)
{
    Console.WriteLine("Площадь квадрата больше.");
}

else
    Console.WriteLine("Площади равны.");

