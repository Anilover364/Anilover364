Console.WriteLine("Введите переменные x,y");
//double x = Convert.ToDouble(Console.ReadLine
//y = Convert.ToDouble(Console.ReadLine());
double a, b, c, d, x1 = 1, y1 = 1;
double.TryParse(Console.ReadLine(), out double x);
double.TryParse(Console.ReadLine(), out double y);
a = x; b=x; c=y;d=y;
if (x1 <= a & x1 <= b & y1 <= c & y1 <= d)
{
    Console.WriteLine("с координатами (x1, y1) лежит внутри прямоугольника");
}
else if(x1 >= a || x1 >= b || y1 >= c || y1 >= d)
    Console.WriteLine("с координатами (x1, y1) не лежит внутри прямоугольника");

<!---
Anilover364/Anilover364 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
