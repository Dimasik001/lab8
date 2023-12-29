<h1 align= "center"> МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ РОССИЙСКОЙ ФЕДЕРАЦИИ ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</h1>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<p align= "center">Лабораторная работа №7</p><br><br><br><br><br><br><br><br>
<p align= "right">Выполнил: Андреев Д.В.</p><br><br><br><br><br><br><br><br>
<p align="center">г. Южно-Сахалинск <br> 2023 год</p><br><br><br><br><br><br><br><br>
<h2 style="text-align: center">Введение</h2>
<p align="justify">PHP — интерпретируемый скриптовый язык программирования общего назначения. Название представляет собой рекурсивный акроним PHP: Hypertext Preprocessor (PHP: предварительный обработчик гипертекста), но изначально оно расшифровывалось как Personal Home Page Tools (Инструменты для создания персональных веб-страниц).</p>
<h2 style="text-align: center">Цели и задачи</h2>
<ol align="justify"> <br>
<h2 align="center">Цели и задачи</h2>
Задачи:
1.Создайте переменную $var и присвойте ей значение 'hello'. Обращаясь к отдельным символам этой строки выведите на экран символ 'h', символ 'e', символ 'o'.<br>
2.Напишите скрипт, который считает количество секунд в часе.<br>
3.Переделайте приведенный код так, чтобы в нем использовались операции +=, -=, *=, /=, ++, --. Количество строк кода при этом не должно измениться. Код для переделки:
<?php
$var = 1;
$var = $var + 12;
$var = $var - 14;
$var = $var * 5;
$var = $var / 7;
$var = $var + 1;
$var = $var - 1;
echo $var;
?> <br>
4.Создайте переменную $a и присвойте ей значение 3. Выведите значение этой переменной на экран. <br>
5.Создайте переменные $a=10 и $b=2. Выведите на экран их сумму, разность, произведение и частное (результат деления). <br>
6.Создайте переменные $c=15 и $d=2. Просуммируйте их, а результат присвойте переменной $result. Выведите на экран значение переменной $result. <br>
7.Создайте переменные $a=10, $b=2 и $c=5. Выведите на экран их сумму. <br>
8.Создайте переменные $a=17 и $b=10. Отнимите от $a переменную $b и результат присвойте переменной $c. Затем создайте переменную $d, присвойте ей значение 7. Сложите переменные $c и $d, а результат запишите в переменную $result. Выведите на экран значение переменной $result. <br>
9.Создайте переменную $text и присвойте ей значение 'Привет, Мир!'. Выведите значение этой переменной на экран. <br>
10.Создайте переменные $text1='Привет, ' и $text2='Мир!'. С помощью этих переменных и операции сложения строк выведите на экран фразу 'Привет, Мир!'.<br>
11.Создайте переменную $name и присвойте ей ваше имя. Выведите на экран фразу 'Привет, %Имя%!'. Вместо %Имя% должно стоять ваше имя. <br>
12.Создайте переменную $age и присвойте ей ваш возраст. Выведите на экран 'Мне %Возраст% лет!'.<br>
13.Создайте переменную $text и присвойте ей значение 'abcde'. Обращаясь к отдельным символам этой строки выведите на экран символ 'a', символ 'c', символ 'e'.<br>
14.	 Дана произвольная строка, например, 'abcde'. Поменяйте первую букву (то есть букву 'a') этой строки на '!'.<br>
15.	 Создайте переменную $num и присвойте ей значение '12345'. Найдите сумму цифр этого числа.<br>
16.	Напишите скрипт, который считает количество секунд в часе, в сутках, в месяце.<br>
17.	 Создайте три переменные - час, минута, секунда. С их помощью выведите текущее время в формате 'час:минута:секунда'.<br>
18.	 Создайте переменную, присвойте ей число. Возведите это число в квадрат (это значит нужно умножить его само на себя). Выведите его на экран.<br>
19.	Переделайте этот код так, чтобы в нем использовались операции +=, -=, *=, /=. Количество строк кода при этом не должно измениться. 
$var = 47;
$var = $var + 7;
$var = $var - 18;
$var = $var * 10;
$var = $var / 20;
echo $var;<br>
20.	 Переделайте этот код так, чтобы в нем использовалась операция .=. Количество строк кода при этом не должно измениться.
$text = 'Я';
$text = $text.' хочу';
$text = $text.' знать';
$text = $text.' PHP!';
echo $text;<br>
21.	 Переделайте этот код так, чтобы в нем использовались операции ++ и --. Количество строк кода при этом не должно измениться.
$var = 10;
$var = $var + 1;
$var = $var + 1;
$var = $var - 1;
echo $var;<br>
22.	 Переделайте этот код так, чтобы в нем использовались операции ++, -- , +=, -=, *=, /=. Количество строк кода при этом не должно измениться.
$var = 10;
$var = $var + 7;
$var = $var + 1;
$var = $var - 1;
$var = $var + 12;
$var = $var * 7;
$var = $var - 15;
echo $var;<br>

<!DOCTYPE HTML>
<html>
<head>
    <meta charset="utf-8">
</head>
<body>
    <input type="button" id="hider" value="Нажмите, чтобы спрятать текст"/>
    <div id="hide">Текст</div>
<script>
    /* ваш код */
</script>
</body>
</html>
19.	Создайте кнопку, при клике на которую, она будет скрывать сама себя.<br>
20.	Напишите простой калькулятор.<br>



Код на PHP
```php
//1 
<?php
 $var = 'abcde';
 echo $var[0]; //выведем букву 'h'
 echo $var[1]; //выведем букву 'e'
 echo $var[4]; //выведем букву 'o'
?><br>
//2
<?php
 echo 60 * 60 * 24;
?><br>
//3
<?php
 $var = 1;
 $var += 12;
 $var -= 14;
 $var *= 5;
 $var /= 7;
 $var++;
 $var--;
 echo $var;
?><br>
//4
<?php
$a = 3;
echo $a;
?><br>
//5
<?php
$a = 10;
$b = 2;
echo $a + $b;
echo $a - $b;
echo $a * $b;
echo $a / $b;
?><br>
//6
<?php
$c = 15;
$d = 2;
$result = $c + $d;
echo $result;
?><br>
//7
<?php
$a = 10;
$b = 2;
$c =5;
echo $a + $b + $c;
?><br>
//8
<?php
$a = 17;
$b = 10;
$c = $a - $b;
$d = 7;
$result = $c + $d;
echo $result;
?><br>
//9
<?php
$text = 'Привет, Мир!';
echo $text;
?><br>
//10
<?php
$text1 = 'Привет, ';
$text2 = 'Мир!';
echo $text1 . $text2;
?><br>
//11
<?php
$name = 'Димас';
echo 'Привет, ' . $name . '!';
?><br>
//12
<?php
$age = 22;
echo 'Мне ' . $age . ' года!';
?><br>
//13
<?php
$text = 'abcde';
echo $text[0];
echo $text[2];
echo $text[4];
?><br>
//14
<?php
$text = 'abcde';
$text[0] = '!';
?><br>
//15
<?php
$num = '12345';
$sum = $num[0] + $num[1] + $num[2] + $num[3] + $num[4];
?><br>
//16
<?php
$hour = 60 * 60;
$day = $hour * 24;
$month = $day * 30;
?><br>
//17
<?php
$hour = 0;
$min = 19;
$sec = 33;
echo $hour . ':' . $min . ':' . $sec;
?><br>
//18
<?php
$a = 3;
$a *= $a;
echo $a;
?><br>
//19
<?php
$var = 47;
$var += 7;
$var -= 18;
$var *= 10;
$var /= 20;
echo $var;
?><br>
//20
<?php
$text = 'Я';
$text .= ' хочу';
$text .= ' знать';
$text .= ' PHP!';
echo $text;
?><br>
//21
<?php
$var = 10;
$var++;
$var++;
$var--;
echo $var;
?><br>

//22
<?php
$var = 10;
$var += 7;
$var++;
$var--;
$var += 12;
$var *= 7;
$var -= 15;
echo $var;
?>
```

CODEWARS
```JavaScript
function findAverage(array) {
  let total = 0;
  let average = 0;
  if (array.length === 0) {
    return 0;
  } else {
    for (let i = 0; i < array.length; i++) {
      total += array[i]
    }
    average = total / array.length
    return average;
  }
}
function findEvenIndex(arr) {
  var sum = 0,
  leftSum = 0;
  for (var i = 0; i < arr.length; i++) {
    sum = sum + arr[i];
  }
  for (var i = 0; i < arr.length; i++) {
    sum = sum - arr[i];
    if (leftSum === sum) {
      return i;
    }
    leftSum = leftSum + arr[i];
  }
  return -1;
}
function alphabetPosition(text) {
  let sentence = text.toLowerCase().split("");
  for (let i = sentence.length - 1; i >= 0; i--) {
    if(sentence[i].match(/[a-z]/) === null) {
      sentence.splice(i, 1);
    }
  }
  let alphaArr = [];
  for (let i = 0; i < 26; i++) {
    alphaArr.push(String.fromCharCode(97 + i));
  }
  return sentence.map(item => alphaArr.indexOf(item) + 1).join(" ");
}
function breakChocolate(n,m) {
 if(n > 0 && m > 0) {
      return n * m - 1;
  } else {
    return 0;
  }
}
```
КОДЕ
```JavaScript
const express = require('express');
const QRCode = require('qrcode');
const app = express();

app.get('/generate', async (req, res) => {
  const url = req.query.url;

  if (!url) {
    return res.status(400).send('URL не указан.');
  }
//QRCode.toDataURL() для генерации QR-кода на основе переданного URL. 
try {
  const qr = await QRCode.toDataURL(url, {
  width: 600, 
  height: 600, 
  color: {
  dark: '#081272', // Цвет  модулей QR-кода
  light: '#ffffff' // Цвет светлых модулей QR-кода
  },
  margin: 10 
  });
  res.send(`<img src="${qr}" />`);
  } catch (err) {
  res.status(500).send('Ошибка при создании QR-кода.');
  }
  });
app.get('/', async (req, res) => {
    res.send("добавить  /generate?url=https://vk.com/dmitriy_andreev65")
  });

app.listen(3000, () => {
  console.log(`Сервер запущен на порту 3000`);
});
```
ПОЧТА
```JavaScript
const nodemailer = require('nodemailer');


const smtpConfig = {
  host: 'smtp.mail.ru',
  port: 587,
  secure: false, // true для SSL, false для других
  auth: {
    user: 'dimasandreev071@mail.ru',
    pass: 'jH6PgYsNgQ6iYz0E3DxV',
  },
};

//  для отправки почты
const transporter = nodemailer.createTransport(smtpConfig);

// Параметры 
const mailOptions = {
  from: 'dimasandreev071@mail.ru',
  to: 'dimasandreev019@gmail.com',
  subject: 'Enotik',
  text: 'Poloskyn',
 
};

// Отправляем 
transporter.sendMail(mailOptions, (error, info) => {
  if (error) {
    return console.log('Ошибка отправки письма:', error);
  }
  console.log('Письмо успешно отправлено:', info.messageId);
});
```
  <h2 style="text-align: center">ВЫВОД</h2>
 PHP — одним из самых популярных серверных языков программирования для веб-разработки. Он используется в следующих сферах:

Веб-программирование. Используется для создания динамических веб-сайтов и веб-приложений. С помощью PHP можно генерировать интерактивные формы, обрабатывать данные, работать с БД и создавать динамический контент.
