int sum = 0;
for (int a = 1; a < 21; a++)
{
    if (a % 3 == 0)
    {
        sum = sum + a;
    }
}
console.writeline($"{sum}");