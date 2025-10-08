using System;

class Program
{
    static void Main()
    {
        int[] a = {1, 3, 4, 6, 8, 34, 5, 56, 23, 79};
        int say = 0;

        foreach (int n in a)
        {
            if (n > 1)
            {
                bool sadedir = true;
                for (int i = 2; i * i <= n; i++)
                {
                    if (n % i == 0)
                    {
                        sadedir = false;
                        break;
                    }
                }

                if (!sadedir)
                    say++;
            }
        }

        Console.WriteLine("Murekkeb eded sayi: " + say);
    }
}
