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
//	1.
//	Автор: Андреев Дмитрий
/*	Дата выполнения:
	Начало: 29.12.2023
	Время выполнения: ~ 1.5 часа*/
echo "Задание 1 ";
echo "Приветствие!";

//	2.
echo "Задание 2 ";
$tvChannel;		//	название телеканала
$manAdress;		//	адрес производителя
$carColor;		//	цвет автомобиля
$waterTemp;		//	температура воды
$phoneModel;	//	модель телефона

//	3.
echo "Задание 3 <br>";
$three = 3;
$five = 5;
$eight = 8;
echo "$three, $five, $eight";
echo "<br>";

$sum = $three + $five + $eight;
echo $result = 2 + 6 + 2 / 5 - 1;
echo "<br><br>";

//	4.
echo "Задание 3 <br>";
$a = 1;
$b = 2;
echo "$a, $b";
echo "<br>";
$c = $a;
$d = $b;
echo "$c, $d";
echo "<br>";
$a = 3;
$b = 4;
echo "$a, $b, $c, $d";
echo "<br><br>";

// 5.
echo "Задание 5 <br>";
define("const1", 41);
define("const2", 33);
echo const1 + const2;
echo "<br><br>";

//	6.
echo "Задание 6 <br>";
$a = 152;
$b = '152';
$c = 'London';
$d = array(152);
$e = 15.2;
$f = false;
$g = true;
var_dump($a, $b, $c, $d, $e, $f, $g);
echo "<br><br>";

//	7.
echo "Задание 7 <br>";
echo "\$a = $a, \$b = $b", PHP_EOL;
echo "<br><br>";

//	8.
echo "Задание 8 <br>";
$first = "Доброе утро";
$second = "дамы";
$third = "и господа";
echo $first . " " . $second . " " . $third, PHP_EOL;
echo "<br><br>";

// 9.
echo "Задание 9 <br>";
$arr1 = [1, 2, 3, 4, 5];
$arr2 = [6, 7, 8, 9, 10];
$arr1["element"] = 25;

unset($arr2[0]);
echo $arr1[2], $arr2[2];
echo "<br>";

var_dump($arr1, $arr2);
echo count($arr1), count($arr2);
echo "<br><br>";

//	10.
echo "Задание 10 <br>";
define("N", 5);

for ($i = 0; $i < N; $i++) {
	echo random_int(-21, 35);
	echo "<br>";
}
echo "<br><br>";

//	11.
echo "Задание 11 <br>";
$sum = 0;
for ($i = 0; $i < N; $i++) {
	$sum += random_int(-21, 35);
}
echo $sum;
echo "<br><br>";

// 12.
echo "Задание 12 <br>";
for ($i = 0, $last = null; $i < N; $i++) {
	$num = random_int(-50, 50);
	echo $num;

	if ($last != null)
		if ($num > $last)
			echo " - Больше предыдущего";
		else if ($num < $last)
			echo " - Меньше предыдущего";
		else
			echo " - Равны";
	$last = $num;
	echo "<br>";
}
echo "<br><br>";

//	13.
echo "Задание 13 <br>";
function Fibb($n)
{
	if ($n <= 1) return 0;

	if ($n == 2) return 1;

	return Fibb($n - 1) + Fibb($n - 2);
}

echo N, " число Фибоначчи = ", Fibb(N);
echo "<br><br>";

//	14.
echo "Задание 14 <br>";
$number = 12345;
do {
	echo $number % 10;
	$number = ($number - $number % 10) / 10;
} while ($number > 0);
echo "<br><br>";

//	15.
echo "Задание 15 <br>";
$number = 12345;
$hasOdds = false;
do {
	$num = $number % 10;
	if ($num % 2 != 0) {
		$hasOdds = true;
		echo $num;
	}
	$number = ($number - $number % 10) / 10;
} while ($number > 0);
if (!$hasOdds) echo "Нечетных цифр не обнаружено!";
echo "<br><br>";

//	16.
echo "Задание 16 <br>";
for ($i = 0; $i < 7; $i++) {
	$arr[$i] = random_int(-10, 10);
}
for ($i = 0; $i < 7; $i++) {
	echo $arr[$i], " ";
}
echo "<br><br>";

//	17.
echo "Задание 17 <br>";
$m = 5;
$n = 5;
for ($i = 0; $i < $m; $i++) {
	$arr[$i] = [];
	for ($j = 0; $j < $n; $j++) {
		$arr[$i][$j] = random_int(-10, 10);
	}
}
echo "<br>";
for ($i = 0; $i < $m; $i++) {
	for ($j = 0; $j < $n; $j++) {
		echo str_pad($arr[$i][$j], 4, " ");
	}
	echo "<br>";
}
echo "<br><br>";

//	18.
echo "Задание 18 <br>";
$N = 20;
for ($i = 1; $i <= $N; $i++) {
	$arr[$i - 1] = $i;
}

//1
echo "1)<br>";
for ($i = 0, $j = 0, $k = 1; $i < $N; $i++) {
	echo $arr[$i], " ";
	if (++$j >= $k) {
		echo "<br>";
		$j = 0;
		$k++;
	}
}

//	2)
echo "<br>2)<br>";
for ($i = 1, $j = 0, $k = 1; $i <= $N; $i++) {
	echo $i, " ";
	if (++$j >= $k) {
		echo "<br>";
		$j = 0;
		$k++;
	}
}
echo "<br><br>";

//	19.
echo "Задание 19 <br>";
echo max($arr);
echo "<br><br>";

//	20.
echo "Задание 20 <br>";
echo min($arr);
echo "<br><br>";

//	21.
echo "Задание 21 <br>";
$arr1 = [];
$arr2 = [];

for ($i = 0; $i < 20; $i++) {
	$arr1[$i] = $arr2[$i] = random_int(-10, 10);
}
for ($i = 2, $j = 1; $i < 20; $i += 3, $j += 2) {
	if ($arr1[$i] > $arr2[$j])
		echo "$arr1[$i] больше $arr2[$j] <br>";
	else if ($arr1[$i] < $arr2[$j])
		echo "$arr1[$i] меньше $arr2[$j] <br>";
	else
		echo "$arr1[$i] и $arr2[$j] равны <br>";
}
echo "<br><br>";

//	22.
echo "Задание 22 <br>";
function func($arr)
{
	foreach ($arr as $num) {
		switch ($num) {
			case 5:
				$res = "пять";
				break;
			case 6:
				$res = "шесть";
				break;
			case 7:
				$res = 7;
				break;
			default:
				$res = "какое-то другое число";
				break;
		}

		echo $res;
		echo "<br>";
	}
}
echo func([4,5,6,7,8]);
echo "<br><br>";

// 23.
echo "Задание 23 <br>";
$a = [];
for ($i = 0; $i < 10; $i++) {
	$a[$i] = random_int(1, 20);
}
$b = [12, 5, 17, 6, 4];

//	1)
echo "1)<br>";
$counter = [];
for ($i = 0; $i < count($b); $i++) {
	$counter[$b[$i]] = 1;
}
for ($i = 0; $i < 10; $i++) {
	if (empty($counter[$a[$i]])) echo $a[$i], " ";
}
//	2)
echo "<br>2)<br>";
for ($i = 0; $i < 10; $i++) {
	if (!in_array($a[$i], $b)) echo $a[$i], " ";
}

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
