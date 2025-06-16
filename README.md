        string[] phrases = {
        "Продуктът е отличен.",
        "Това е страхотен продукт.",
        "Постоянно ползвам този продукт.",
        "Това е най-добрият продукт от тази категория."
    };

        string[] events = {
        "Чувствам се добре.",
        "Успях да се променя.",
        "Той направи чудо.",
        "Спечелих! Случи се чудо!",
        "Не мога да повярвам, но успях да превъзмогна себе си.",
        "Опитайте и вие. Аз съм много доволна."
    };

        string[] firstNames = { "Калина", "Гергана", "Стела", "Елена", "Катя" };
        string[] lastNames = { "Иванова", "Петрова", "Кирова" };
        string[] cities = { "София", "Пловдив", "Варна", "Русе", "Бургас", "Карлово", "Сопот" };

        
        string phrase = phrases[0];
        string evnt = events[0];
        string firstName = firstNames[0];
        string lastName = lastNames[0];
        string city = cities[0];

        Console.WriteLine($"{phrase} {evnt} – {firstName} {lastName}, {city}");
        //samo taka znaeh kak da q naprava i kogato smenqm indeksite na imenata i reklamite samo togava se smenqt ot konzolata ne znam kak da gi smenqm na random
    }
}




        static void Main(string[] args)
        {
            
            
            int[] numbers = new int[10];

            int sumPositive = 0;
            int zeroCount = 0;
            int min = int.MaxValue;
            int max = int.MinValue;
            for (int i = 0; i < 10; i++)
            {
                Console.Write($"Въведи число {i + 1}: ");
                numbers[i] = int.Parse(Console.ReadLine());

                if (numbers[i] > 0)
                    sumPositive += numbers[i];

                if (numbers[i] == 0)
                    zeroCount++;

                if (numbers[i] < min)
                    min = numbers[i];

                if (numbers[i] > max)
                    max = numbers[i];
            }
            
            Console.WriteLine("Сума на положителните елементи: " + sumPositive);
            Console.WriteLine("Брой на нулевите елементи: " + zeroCount);
            Console.WriteLine("Най-малък елемент: " + min);
            Console.WriteLine("Най-голям елемент: " + max);

        }
    }
}






 static void Main(string[] args)
 {
     Console.WriteLine("Dai broi chisla");
     int n = int.Parse(Console.ReadLine());
     Console.WriteLine("Chislata sa");
     int[] numbers = new int[n];
     for (int i = 0; i < n; i++)
     {
         numbers[i] = int.Parse(Console.ReadLine());
     }
     for (int i = n - 1; i >= 0; i--)
     {
         
     }
     Console.WriteLine("Obyrnati sa: ");
     Console.WriteLine(string.Join(" ", numbers));
 }
