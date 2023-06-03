# Задание 1 #

### Задание 1 ###
Необходимо создать переменную в которой будет храниться температура в градусах Цельсия, преобразовать значение в температуру по фаренгейту.
Формула перевода градусов Цельсия в градусы Фаренгейта: градусы Фаренгейта = (9 / 5) * градусы Цельсия + 32
Вывести в консоль температуру в Цельсиях и Фаренгейтах.

### Задание 2 ###
Необходимо создать переменную name, записать в эту переменную свое имя. Необходимо также создать переменную admin и присвоить этой переменной значение из переменной name. Вывести значение переменной admin в консоль.
_________________________________________________________________________________________

# Задание 2 #

### Задание 1 ###
Создать переменные num1, num2 которые пользователь вводит с клавиатуры
Проверьте, что переменная num1 равна или меньше 1, а переменная num2 больше или равна 3.

### Задание 2 ###
Перепишите код к тернарному оператору

let test = true;
if (test === true) {
console.log('+++');
} else {
console.log('---');
}

### Задание 3 ###
В переменной day лежит какое-то число из интервала от 1 до 31. Определите в какую декаду месяца попадает это число (в первую, вторую или третью).


### Задание 4 ###
Необязательное задание. (Если вам показалось домашнее задание простым, выполняем данный пункт)
(Для решения задания вам потребуется оператор остаток от деления %, например 10%3 === 1 , десять разделить на 3, остаток 1, второй пример 7 % 5, тут остаток от деления будет 2, ну и 3 пример это 14 % 10 === 4, остаток от деления на 10 будет равен 4)

Необходимо от пользователя получить число.
Необходимо вывести разряды числа, а именно: количество сотен, десятков и единиц.

Пример:
Пользователь ввел число 163. Программа должна вывести:
"В числе 163 количество сотен: 1, десятков: 6, единиц: 3"

Пример 2:
Пользователь ввел число 74. Программа должна вывести:
"В числе 74 количество сотен: 0, десятков: 7, единиц: 4"

Пример 3:
Пользователь ввел число 9537. Программа должна вывести:
"В числе 9537 количество сотен: 5, десятков: 3, единиц: 7"

Уточнение: пользователь всегда вводит корректное положительное целое число.
_________________________________________________________________________________________

# Задание 3 #

### Задание 1 ###
Создайте функцию которая возводит переданное число в куб, необходимо вывести в консоль результат 2^3 степени + 3 ^ 3 степени

### Задание 2 ###
Пользователь вводит с клавиатуры число, если ввёл текст, необходимо вывести что значение задано неверно
Создать фукнцию, которая высчитывает 13% от данного числа и выводит в консоль текст "Размер заработной платы за вычетом налогов равен значение"

### Задание 3 ###
Пользователь с клавиатуры вводит 3 числа, необходимо создать функцию, которая определяет максимальное значение среди этих чисел

### Задание 4 ###
Необходимо реализовать четыре функции, каждая функция должна принимать по два числа и выполнять одну из операций (каждая функция выполняет одну из них):
1. Сложение
2. Разность
3. Умножение
4. Деление
Необходимо сделать так, чтобы функция вернула число, например выражение console.log(sum(2, 6)); должно вывести число 8 в консоль (sum - функция сложения в данном примере, ваши названия функций могут отличаться). Округлять значения, которые возвращают функции не нужно, однако, обратите внимание на разность, функция должна вычесть из большего числа меньшее, либо вернуть 0, если числа равны. Функциям всегда передаются корректные числа, проверки на NaN, Infinity делать не нужно.

_________________________________________________________________________________________

# Задание 4 #

### Задание 1 ###
Необходимо с помощью цикла for вывести следующие 11 строк в консоль:
0 – это ноль
1 – нечетное число
2 – четное число
3 – нечетное число
…
10 – четное число

### Задание 2 ###
Дан массив [1, 2, 3, 4, 5, 6, 7]
Сделайте из этого массива следующий [1, 2, 3, 6, 7]

### Задание 3 ###
Используя Math.random() вам необходимо генерировать цифры от 0 до 9, и создать массив состоящий из 5 таких элементов
1. Рассчитать сумму элементов этого массива
2. Найти минимальное число
3. Найти есть ли в этом массиве число 3

### Задание 4 ###
*Необязательное задание. *
Необходимо вывести горку в консоль (используя цикл for), как показано на рисунке, только у вашей горки должно быть 20 рядов, а не 5:
```
x
xx
xxx
xxxx
xxxxx
```
_________________________________________________________________________________________

# Задание 5 #

### Задание 1 ###
Дан объект numbers. Необходимо в консоль вывести все значения больше или равные 3.

```javascript
const numbers = {
    keyin1: 1,
    keyin2: 2,
    keyin3: 3,
    keyin4: 4,
    keyin5: 5,
    keyin6: 6,
    keyin7: 7,
};
```

### Задание 2 ###
Необходимо из объекта, который лежит в константе post вывести значения, к которым приписан комментарий, в консоль.

```javascript
const post = {
    author: "John", // вывести этот текст
    postId: 23,
    comments: [
        {
            userId: 10,
            userName: "Alex",
            text: "lorem ipsum",
            rating: {
                likes: 10,
                dislikes: 2, // вывести это число
            },
        },
        {
            userId: 5, // вывести это число
            userName: "Jane",
            text: "lorem ipsum 2", // вывести этот текст
            rating: {
                likes: 3,
                dislikes: 1,
            },
        },
    ],
};
```

### Задание 3 ###
Дан массив products, необходимо цену каждого продукта уменьшить на 15% используя метод forEach.

```javascript
const products = [
    {
        id: 3,
        price: 200,
    },
    {
        id: 4,
        price: 900,
    },
    {
        id: 1,
        price: 1000,
    },
];
```

### Задание 4 ###
1. Необходимо вывести в консоль массив продуктов в котором есть хоть одна фотография используя метод filter. Исходные данные - массив products.
2. Необходимо отсортировать массив products используя метод sort по цене, начиная с самой маленькой, заканчивая самой большой ценой, после чего вывести отсортированный массив в консоль.

```javascript
const products = [
    {
        id: 3,
        price: 127,
        photos: ["1.jpg", "2.jpg",],
    },
    {
        id: 5,
        price: 499,
        photos: [],
    },
    {
        id: 10,
        price: 26,
        photos: ["3.jpg",],
    },
    {
        id: 8,
        price: 78,
    },
];
```

### Задание 5 ###
Дано 2 массива 
const en = ["mon", "tue", "wed", "thu", "fri", "sat", "sun"];
const ru = ["понедельник", "вторник", "среда", "четверг", "пятница", "суббота", "воскресенье"];
Вам необходимо объединить 2 этих массива, чтобы значения первого массива были ключами, а значения второго массива — значениями.