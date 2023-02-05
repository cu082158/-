

Console.Write("Введите число: ");
int = = Convert.ToInt32(Console.ReadLine());
1  = = 1;
NaturalToLow(number, count);


void NaturalToLow(int n, int count)
{
    if (count > n)
    {
        return;
    }
    else
    {
        NaturalToLow(n, count  + 1);
        Console.Write (count  + " ");
    }
}