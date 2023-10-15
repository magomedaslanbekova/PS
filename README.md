## Контрольная работа
Данная работа необходима для проверки ваших знаний и навыков по итогу прохождения первого блока обучения на программе Разработчик. Мы должны убедится, что базовое знакомство с IT прошло успешно.

Задача алгоритмически не самая сложная, однако для полноценного выполнения проверочной работы необходимо:

1. Создать репозиторий на GitHub
2. Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете её в отдельный метод)
3. Снабдить репозиторий оформленным текстовым описанием решения (файл README.md)
4. Написать программу, решающую поставленную задачу
5. Использовать контроль версий в работе над этим небольшим проектом (не должно быть так, что всё залито одним коммитом, как минимум этапы 2, 3, и 4 должны быть расположены в разных коммитах)

Задача: Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

**Примеры:**

[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]

[“Russia”, “Denmark”, “Kazan”] → []

## Решение 
Пишем метод создания нашего начального массива.
После  этого  создаем функцую Random.Next для выбора случайных слов из нашего массива. Ставим условие *if* чтоб он выбирал только те слова у которых 3 символа или же меньше. И в конце вывод наших слов с помощью *System.Console.WriteLine(randomWord "Вот числа которое равно 3 или меньше 3 символов");*

 После условия пишем *else* для того чтоб если не окажится слов меньше 3 символов или равному 3 симлволов. И также выводим   *System.Console.WriteLine("Нету слова которая состоит из 3 или равно 3 символом");* 
