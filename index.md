## Welcome to Judes blog
This is where I will put everything I have learnt in my college course. 

### About me

I have no clue what I am doing half of the time, but the other half now thats when I get work done.

```markdown
This is what I've been working on

using System;
using System.Diagnostics;
using System.Security;

namespace Judeipidia
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Please input an animal: ");
            string fake = Console.ReadLine();
            Process.Start(@"C:\Program Files (x86)\Google\Chrome\Application\chrome.exe",
              "https://www.youtube.com/watch?v=dQw4w9WgXcQ");

            bool aminal = true;
            while (aminal == true)
            {
                Console.ForegroundColor = ConsoleColor.Green;
                Console.Title = "Judeipidia";

                Console.WriteLine("Please input an animal: ");
                string animal = Console.ReadLine();
                Process.Start(@"C:\Program Files (x86)\Google\Chrome\Application\chrome.exe",
                  "https://en.wikipedia.org/wiki/" + animal);

                Console.ForegroundColor = ConsoleColor.Red;

                Console.WriteLine("Press input to rerun or input 'N' to end");
                string answer = Console.ReadLine();
                answer.ToUpper();

                if (answer == "N")
                {
                    Environment.Exit(0);
                }
            }
        }
    }
}
```

For more details contact me at [Juderafferty64@gmail.com](Juderafferty64@gmail.com).
