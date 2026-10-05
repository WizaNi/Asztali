# Ismetles.cs

 ``` c#
            // GYAKROLAS FELADAT 1.
            // Kerj be egy egesz szamot ird ki h pozitiv, negativ, 0, paros, paratlan
            // Kerj pontszamot 0-100 switch if lanc: 39-1 59-2 79-3 89-4 100-5


            /*
            
            Console.Write("Adj meg egy egesz szamot: ");
            string szam = Console.ReadLine();
            int szamInt = int.Parse(szam);

            string szamP;

            if (szamInt > 0)
            {
                szamP = "pozitiv";
            }
            else if (szamInt < 0)
            {
                szamP = "negativ";
            }
            else
            {
                szamP = "nulla";
            }

            if (szamInt % 2 == 0)
            {
                if (szamInt != 0)
                {
                    Console.WriteLine("A szam paros es " + szamP);
                }
            }
            else if (szamInt % 2 != 0)
            {
                Console.WriteLine("A szam paratlan es " + szamP);
            }
            else if ( szamInt == 0)
            {
                Console.WriteLine("A szam " + szamP); 
            }
            */

            /*
            List<int> numbers = new List<int>() { 3, 7, 1, 9, 4 };
            List<string> names = new List<string>();
            names.Add("Anna");
            names.Add("Gabor");

            Console.WriteLine("numbers: ");
            for (int i = 0; i < numbers.Count; i++)
            {
                Console.WriteLine(" - " + numbers[i]);
            }
            Console.WriteLine();

            Console.WriteLine("names: ");
            for (int i = 0; i < names.Count; i++)
            {
                Console.WriteLine(" - " +  names[i]);
            }
            Console.WriteLine();

            Console.WriteLine("elem hozzadasa (2. hely, Eszter): ");
            names.Insert(1, "Eszter");
            foreach (string name in names)
            {
                Console.WriteLine(" - " + name);
            }
            Console.WriteLine();

            Console.WriteLine("elem torlese (Gabor");
            names.Remove("Gabor"); //names.RemoveAt(2)
            foreach(string name in names)
            {
                Console.WriteLine(" - " + name);
            }
            Console.WriteLine();

            names.Add("Noemi");
            names.Add("Eva");
            names.Add("Zoli");
            Console.WriteLine("names in order: ");
            List<string> sorted = new List<string>(names);
            sorted.Sort();
            foreach (string name in sorted)
            {
                Console.WriteLine(" - " + name);
            }
            Console.WriteLine();

            Console.WriteLine("numbers: ");
            foreach(int item in numbers)
            {
                Console.WriteLine(" - " + item);
            }
            Console.WriteLine();

            Console.WriteLine("2-es indexe: " + numbers.IndexOf(1));
            Console.WriteLine();

            int firstEven = numbers.Find(szam => szam % 2 == 0);
            Console.WriteLine("Elso paros: " + firstEven);
            Console.WriteLine();

            Console.WriteLine("Elemek torlese...");
            numbers.Clear();
            Console.WriteLine("Elemek szama: " + numbers.Count);

            */
 ```

---

## [10.05.md](../../Notes/1005.md)

>ismetles
