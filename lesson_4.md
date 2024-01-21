# Домашнее задание к занятию "4. Циклы"

### Описание.

Вам необходимо внутри static void Main(string[] args) написать решение 4 задач. Можно использовать операторы верхнего уровня. 

1. С помощью цикла for (или while) выведите первые 10 чисел Фиббоначи (см. Задание из 3 урока)
2. Используя цикл for, выведите все чётные числа от 2 до 20
3. С помощью вложенных циклов for выведите таблицу умножения от 1 до 5. Каждая строка таблицы должна быть выведена в отдельной строке.
4. Дана строка string password = "qwerty"; Напишите программу для ввода пароля, которая считывает пользовательский ввод Console.ReadLine. Подсказка: используйте do-while

Шаблон программы
```csharp
namespace HomeWork
{
    internal class Program
    {
        private static void Fibonaccy() 
        {
            for (; ; ) { } // пример. Цикл может быть любой, если в задаче не указано, какой использовать
            // для вывода используйте Console.WriteLine

        }

        private static void Even() 
        {
            for (; ; ) { } // аналогично
        }

        private static void Table() { }

        private static void Password() 
        {
            string password = "qwerty"; // пароль задаётся в начале
            //в цикле проверяется ввод и выводится результат
        }

        static void Main(string[] args)
        {
            Fibonaccy();
            Even();
            Table();
            Password();
        }
    }
}
```

Код можно сбросить файлом, либо используйте Pastebin`https://pastebin.com/`
