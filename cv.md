#Anna Zubaryk
*38 years old*


###Place of residence
*Belarus, Minsk*


###Contacts
*tel.:+375445540263*
*email:annazubaryk@tut.by*


###Education
*2000-2006 Belarusian Technical University, faculty Instrumentation, specialty security technology
*2003-2006 Belorusian State Economic University, course Business economics and management
*2019-until now independent study of english 
*2020(6 month) school **Stream Line**
*2020(1 month) "Intro to IT course" **Leverix Group**
*2021-until now **way up**:web-desing, web-layout, JavaScript
and work in Visual Studio Code, codepen, figma


###Work examples

```
function showMessage (firstName, lastName) {
    const fullName = `${firstName} ${lastName}`;
    console.log(fullName);
}

showMessage ('Anna', 'Zubaryk');

```
========

```
<!DOCTYPE html>
<html lang="ru">
<head>
	<meta charset="UTF-8">
	<title>Верстка современного сайта</title>
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@900&family=Open+Sans&family=Ubuntu:wght@400;700&display=swap" rel="stylesheet">
	<link rel="stylesheet" href="css/main.css">
</head>
<body>
	<header id="header" class="header">
		<div class="container">
			<img src="img/logo (1).png" alt="WAYUP" class="logo">
						<div class="wripper">
				<div class="offer">
					<h1 class="title">
						С помощью верстки <br> я создам ту жизнь, о которой <br> <span>мечтаю!</span>
					</h1>
					<p class="intro">
						Мои стремления + настойчивость позволят мне достичь чего угодно. Я не верю в это. Я знаю это на 100%. Меня не остановить!
					</p>
					<a href="#" class="btn">Двигаться к мечте</a>
				</div>
				<img src="img/desktop.png" alt="code desktop" class="desktop">
			</div>
		</div>
	</header>
	<section id="learn" class="learn">
		<div class="container">
		<h2 class="section-title">Что меня ждет впереди</h2>
			<div class="skills">
				<div class="skill">
					<img src="img/icon1.jpg.png" alt="code icon1" class="icon1">
					<h3 class="skill-title">
						Свободное время
					</h3>
					<p class="skill-text">
					Мне нужно свободное время на семью и самое настоящее
					</p>
				</div>
				<div class="skill">
					<img src="img/icon2.jpg.png" alt="code icon2" class="icon2">
					<h3 class="skill-title">
						Яркие путешествия
					</h3>
					<p class="skill-text">
					Работать откуда угодно - что может быть лучше?
					</p>
				</div>
				<div class="skill">
					<img src="img/icon3.jpg.png" alt="code icon3" class="icon3">
					<h3 class="skill-title">
						Создание ценности
					</h3>
					<p class="skill-text">
					Нет ничего сильнее, чем жить не просто так, создавая ценность
					</p>
				</div>
			</div>
	</section>
	<section id="mail" class="mail">
		<div class="container">
			<h2 class="section-title">Форма заказа билета в будущее</h2>	
			<form action="#" class="form">
				<input type="name" placeholder="Имя" name="имя" class="input" required><br>
				<input type="email" placeholder="E-mail" name="email" class="input" required><br>
				<input type="tel" placeholder="Телефон" name="phone" class="input" required><br>
				<input type="where" placeholder="Куда я полечу в ближайшее время" name="where" class="input" required><br>
				<button type="submit" class="btn btn-form">Двигаться к мечте</button>
			</form>
				</div>
				
			</div>
		</div>
	</section>
	<footer id="footer" class="footer">
		<div class="container">
			<p class="credits">
				© Все мои мечты защищены моим трудолюбием)
			</p>
		</div>
	</footer>
</body>
</html>
```
=====================================================================================
```const array = [
    'я в Симбирск,',
    'в трактире.',
    'с утра',
    'В ту же ночь',
    'Я остановился',
    'для закупки', 
    'что и было поручено Савельичу.',
    'приехал,',
    'где должен был',
    'нужных вещей',
    'отправился по лавкам',
    'пробыть сутки',
    'Савельич'
];
array[0] = 'В ту же ночь'
array[1] = 'приехал'
array[2] = 'я в Симбирск,'
array[3] = 'где должен был'
array[4] = 'пробыть сутки'
array[5] = 'для закупки'
array[6] = 'нужных вещей'
array[7] = 'что и было поручено Савельичу.'
array[8] = 'Я остановился'
array [9] = 'в трактире.'
array[10] = 'Савельич'
array[11] = 'с утра'
array[12] = 'отправился по лавкам'
const result = array;
console.log(result.join(' '));
```
=======================================================================================
```
const time = 2;
const speedOfFirst = 95;
const speedOfSecond = 114;
let s1 = (speedOfFirst + speedOfSecond)*2; 
console.log (s1);
```
========================================================================================
```
<!DOCUMENT>
<html>
  <head>
    <title>Задача 1</title>
  </head>
  <body>
    <h1 class = "title">Оформление текста</h1>
    <p>
     Lorem Ipsum - это просто фиктивный текст в полиграфической и наборной индустрии. Lorem Ipsum был стандартным фиктивным текстом в отрасли с 1500-х годов, когда неизвестный типограф взял камбуз шрифта и скремблировал его, чтобы сделать книгу образцов шрифта. Он пережил не только пять веков, но и скачок в электронный набор, оставшись практически неизменным. Он был популяризирован в 1960-х годах с выпуском листов Letraset, содержащих отрывки Lorem Ipsum, а в последнее время - с помощью программного обеспечения для настольных издательских систем, такого как Aldus PageMaker, включая версии Lorem Ipsum.
    </p>
    <h2 class = "subtitle">Заголовок второго уровня</h2>
    <p>
      Давно установлено, что читатель будет отвлекаться на удобочитаемое содержимое страницы при просмотре ее макета. Смысл использования Lorem Ipsum в том, что он имеет более или менее нормальное распределение букв, в отличие от использования «Контент здесь, контент здесь», что делает его похожим на читаемый английский. Многие настольные издательские пакеты и редакторы веб-страниц теперь используют Lorem Ipsum в качестве текста модели по умолчанию, а поиск по запросу «lorem ipsum» обнаружит многие веб-сайты, все еще находящиеся в зачаточном состоянии. С годами появились разные версии, иногда случайно, иногда специально (с добавлением юмора и т.п.).
    </p>
    <ul class = "list">
      <li>элемент</li>
      <li>элемент</li>
      <li>элемент</li>
    </ul>
  </body>  
  
</html>
```
======================================================================================
```
body {
  font-family: Arial, sans-serif;
  font-size: 16px;
  color: #333;
  line-height: 1.5;
}
.title {
  font-size: 40px;
  color: #f03333;
  line-height: 1.2;
  text-transform: uppercase;
}
.subtitle {
  font-size: 30px;
  color: #12ac11;
  line-height: 1.2;
  text-decoration-line: underline;
}
.list {
  font-size: 20px;
  color: #444;
  font-style: italic;
  list-style: square;
}
```

###Experience
Since 2003 work in Open Joint Stock Company "Peleng", communication ingineer and maintenanceof secutity and fire systems.Organizationof correct operation and tymely repair of communications and fair alarm sistem, as well as uninterrupted operation of automation systems.


###Hobby
In my freetime I sports, also learn languages and something new. 
