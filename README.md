using System;
using System.Collections.Generic;
using System.Diagnostics;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace POTATOCOENER
{
    internal class Menu
    {
        static void menu()
        {
            var menu = new List<string>()
            {
                "------------- MENU LIST -------------",
                "1. Regular",
                "2. Large",
                "3. Jumbo",
                "4. Mega",
                "5. Giga",
                "6. Tera",
            };
            foreach (string i in menu)
            {
                Console.WriteLine(i);
            }
        }
        static void flavor()
        {
            var flavor = new List<string>()
            {
                "------------- FLAVOR LIST -------------",
                "1. Barbeque",
                "2. Cheese",
                "3. Sour and Cream",
            };
            foreach (string i in flavor)
            {
                Console.WriteLine(i);
            }
        }
    }
    internal class Item
    {
        static void price()
        {
            var price = new List<string>()
            {
                "------------- PRICE LIST -------------",
                "1. Regular                      P35.00",
                "2. Large                        P60.00",
                "4. Mega                        P119.00",
                "5. Giga                        P189.00",
                "6. Tera                        P220.00",
            };
            foreach (string i in price)
            {
                Console.WriteLine(i);
            }
        }
    }
}
