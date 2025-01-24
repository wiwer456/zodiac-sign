```C#
string zd = "";

Console.WriteLine("Введите ваше имя:");
string name = Console.ReadLine();

Console.WriteLine("Введите вашу фамилию:");
string surename = Console.ReadLine();

Console.WriteLine("Введите ваше число рождения:");
int date = Convert.ToInt32(Console.ReadLine());

Console.WriteLine("Введите ваш месяц рождения:");
int month = Convert.ToInt32(Console.ReadLine());

if (((date >= 21 && date <= 31) && month == 3) || ((date >= 1 && date <= 19) && month == 4))
{
    zd = "Овен";
}else if (((date >= 20 && date <= 30) && month == 4) || ((date >= 1 && date <= 20) && month == 5))
{
    zd = "Телец";
}
else if (((date >= 21 && date <= 31) && month == 5) || ((date >= 1 && date <= 21) && month == 6))
{
    zd = "Близнецы";
}
else if (((date >= 22 && date <= 30) && month == 6) || ((date >= 1 && date <= 22) && month == 7))
{
    zd = "Рак";
}
else if (((date >= 23 && date <= 31) && month == 7) || ((date >= 1 && date <= 22) && month == 8))
{
    zd = "Лев";
}
else if (((date >= 23 && date <= 31) && month == 8) || ((date >= 1 && date <= 22) && month == 9))
{
    zd = "Дева";
}
else if (((date >= 23 && date <= 30) && month == 9) || ((date >= 1 && date <= 23) && month == 10))
{
    zd = "Весы";
}
else if (((date >= 24 && date <= 31) && month == 10) || ((date >= 1 && date <= 22) && month == 11))
{
    zd = "Скорпион";
}
else if (((date >= 23 && date <= 30) && month == 11) || ((date >= 1 && date <= 21) && month == 12))
{
    zd = "Стрелец";
}
else if (((date >= 22 && date <= 31) && month == 12) || ((date >= 1 && date <= 20) && month == 1))
{
    zd = "Козерог";
}
else if (((date >= 21 && date <= 31) && month == 1) || ((date >= 1 && date <= 18) && month == 2))
{
    zd = "Водолей";
}
else if (((date >= 19 && date <= 29) && month == 2) || ((date >= 1 && date <= 20) && month == 3))
{
    zd = "Рыбы";
}

Console.WriteLine("---------------------------------------------------------S");
Console.WriteLine($"\nВаше имя: {name}, Ваша фамилия: {surename}, Ваш знак зодиака: {zd}");
```
