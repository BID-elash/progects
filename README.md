# progects
здесь содержится "большая часть" всех проектов сделанных для заданий Кода Будущего.

1й проект (интерактив с джава):
HTML:
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>интерактив_с_джава</title>
</head>
<body>
	<script src="коджава.js"></script>
</body>
</html>

JavaScript:
alert('привет, я диалоговое окно');
alert('мой создатель создал меня 2 минуты назад');


2й проект (календарь):
HTML:
<!DOCTYPE html>
<html>
<head>
	<link rel="stylesheet" href="цвет.css">
	<title>календарь</title>
</head>
<body>
	<header>
		<h1>КАЛЕНДАРЬ</h1>
		<nav>
			<ul>
				<li>
					<a href="https://youtu.be/dQw4w9WgXcQ?t=1">о нас</a>
				</li>
			</ul>
		</nav>
	<table>
		<tr>
		<th colspan="7">НОЯБРЬ 2023</th>
		</tr>
		<tr>
			<td id="a">пн</td>
			<td id="a">вт</td>
			<td id="a">ср</td>
			<td id="a">чт</td>
			<td id="a">пт</td>
			<td id="a">сб</td>
			<td id="a">вс</td>
		</tr>
				<tr id="c">
			<td></td>
			<td></td>
			<td>1</td>
			<td>2</td>
			<td>3</td>
			<td id="b">4</td>
			<td id="b">5</td>
		</tr>
				<tr id="d">
			<td>6</td>
			<td>7</td>
			<td>8</td>
			<td>9</td>
			<td>10</td>
			<td id="b">11</td>
			<td id="b">12</td>
		</tr>
				<tr id="c">
			<td>13</td>
			<td>14</td>
			<td>15</td>
			<td>16</td>
			<td>17</td>
			<td id="b">18</td>
			<td id="b">19</td>
		</tr>
				<tr id="d">
			<td>20</td>
			<td>21</td>
			<td>22</td>
			<td>23</td>
			<td>24</td>
			<td id="b">25</td>
			<td id="b">26</td>
		</tr>
				<tr id="c">
			<td>27</td>
			<td>28</td>
			<td>29</td>
			<td>30</td>
			<td></td>
			<td id="b"></td>
			<td id="b"></td>
		</tr>
	</table>
		</header>
		<footer>
			<p>адресс: *******</p>
			<p>номер: 8-***-***-**-**</p>
			<p>эл.почта: ********.gmail.com</p>
			<p>соц.сети: *******</p>
			<p>автор.права: *******</p>
		</footer>
</body>
</html>

CSS:
table{
	background-color:black ;text-align: center;
	width:35%;
	border: none
}
th{
	color: none;text-align: center;
	background-color: tan;
	border: none;
}
#a{
	color: white; text-align: center;
	background-color: black;
	border: none;
}
#b{
	color: red;text-align: center;
	border: none;
}
#c{
	color: none;text-align: center;
	background-color: lightgrey;
	border: none;
}
#d{
	color: none;text-align: center;
	background-color: white;
	border: none;
}
p{
	color: white;
	background-color: black;
}

3й проект (кнопка):
HTML:
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" type="text/css" href="кнопка_цвет.css">
	<title>кнопка</title>
</head>
<body>
	<h1>
		<a href="https://youtu.be/dQw4w9WgXcQ?t=1">
			<button class="red">не нажимать</button>
		</a>
	</h1>
</body>
</html>

CSS:
.red{
	background-color: darkred;
	color: red;
	padding: 10px;
	border: none;
	cursor: pointer;
}

4й проект (пицца):
HTML:
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>пицца</title>
</head>
<body>
	<script src="пицца.js"></script>
</body>
</html>

JavaScript:
result = confirm('хотите заказать пиццу?');
alert(result);

5й проект (почему коты стали моими любимыми животнами):
HTML:
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Почему коты стали моими любимыми животнами?</title>
	<link rel="stylesheet" type="text/css" href="коты.css">
</head>
<body>
	<script src="коты_ява.js"></script>

	<header>
		<h2>Почему коты стали моими любимыми животнами?</h2>
	</header>

	<main>
		<section>
			<h1>они пушистые</h1>
			<p><img src="https://krot.club/uploads/posts/2022-03/thumbs/1646156193_42-krot-info-p-smeshnie-tolstie-koti-smeshnie-foto-45.jpg"></p>
		</section>

		<section>
			<h1>они мало едят</h1>
			<p><img src="https://cs9.pikabu.ru/post_img/2019/11/26/9/1574777615141451430.png"></p>
		</section>
	
		<section>
			<h1>их можно гладить</h1>
			<p><img src="https://www.hvoost.ru/upload/medialibrary/ac3/ac3a0f7e2f07bae553cc03459376b051.jpg"></p>
		</section>
	
		<section>
			<h1 id="gal">галерея</h1>
			<p>
				<h1><img src=https://s09.stc.yc.kpcdn.net/share/i/12/12147773/wr-960.webp></h1>

				<h1><img src=https://memepedia.ru/wp-content/uploads/2023/01/kot-dingus-mem-360x270.jpg></h1>

				<h1><img src=https://scientificrussia.ru/images/s/szs-full.jpg></h1>

				<h1><img src=https://pm1.aminoapps.com/6915/4a72da8c367fc9562194a1905920a1f628382a02r1-604-561v2_uhq.jpg></h1>

				<h1><img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSESxGiJLZ4M79ut1VQw3JZULCNbIf8RmEaNA&usqp=CAU></h1>

				<h1><img src=https://cs14.pikabu.ru/post_img/2022/01/31/10/164364607316053554.jpg></h1>
			</p>
		</section>
	</main>

	<footer>
		<h5 id="end">номер телефона (8-***-***_**-**)</h5>
		<h5 id="end">почта (***********.gmail.com)</h5>
	</footer>
</body>
</html>

CSS:
h2{
	background-color: tan;
	text-align: center;
}

li{
	 style="front-size: 18px;"
}

#end{
	color: white;
	background-color: black;
}

#gal{
	background-color: darkcyan;
	text-align: center;
}

h1{
	background-color: green;
	text-align: center;
}

p{
	text-align: center;
}

JavaScript:
result = confirm('Привет, вам нравятся коты?');
alert(result);

6й проект (рецепты):
HTML:
<!DOCTYPE html>
<head>
	<title>рецепты</title>
</head>
<html>
<body>
	<div id="why">
		<h1 style="color: darkred; font-size: 60px;">мои любимые рецепты
		</h1>
	</div>
	<ul>
		<li><a href="#oli">1 рецепт</a></li>
		<li><a href="#tsez">2 рецепт</a></li>
		<li><a href="#pel">3 рецепт</a></li>
	</ul>
	<div id="oli">
		<h1>
	<li style="font-size: 32px;">ОЛИВЬЕ</li>
	<li style="font-size: 20px;">начинка:</li>
	<li style="font-size: 15px;">картофель</li>
	<li style="font-size: 15px;">морковь</li>
	<li style="font-size: 15px;">яйца</li>
	<li style="font-size: 15px;">колбаса(варённая)</li>
	<li style="font-size: 15px;">огурцы(маренованные)</li>
	<li style="font-size: 15px;">горох</li>
	<li style="font-size: 15px;">майонез</li>
	<li><a href="#why">хаб</a></li>
		</h1>
	</div>
	<div id="tsez">
		<h1>
	<li style="font-size: 32px;">САЛАТ ЦЕЗАРЬ</li>
	<li style="font-size: 20px;">начинка:</li>
	<li style="font-size: 15px;">мясо(куринное)</li>
	<li style="font-size: 15px;">сухарики</li>
	<li style="font-size: 15px;">сыр</li>
	<li style="font-size: 15px;">помидоры(черри)</li>
	<li style="font-size: 15px;">салат(зелень)</li>
	<li style="font-size: 15px;">МАЙОНЕЗ</li>
	<li><a href="#why">хаб</a></li>
		</h1>
	</div>
	<div id="pel">
		<h1>
	<li style="font-size: 32px;">ПЕЛЬМЕНИ</li>
	<li style="font-size: 20px;">тесто:</li>
	<li style="font-size: 15px;">яйца</li>
	<li style="font-size: 15px;">мука</li>
	<li style="font-size: 20px;">мясо:</li>
	<li style="font-size: 15px;">на выбор</li>
	<li><a href="#why">хаб</a></li>
		</h1>
	</div>
</body>
</html>

8й проект (сумма двух чисел и не только):
HTML:
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>сумма</title>
</head>
<body>
	<script src="сумма_интер.js"></script>
</body>
</html>

JavaScript:
alert("привет");
let num1=parseInt(prompt("первое число"));
let num2=parseInt(prompt("второе число"));
let num3=parseInt(prompt("что сделать?"));
summa();
proizvedenie();
delenie();
raznost();
function summa(){
	alert(`результат: ${num1 + num2}`);
}
function proizvedenie(){
	alert(`результат: ${num1 * num2}`);
}
function delenie(){
	alert(`результат: ${num1 / num2}`);
}
function raznost(){
	alert(`результат: ${num1 - num2}`);
}

9й проект (таблицалюбимыхигр):
HTML:
<!DOCTYPE html>
<html>
<head>
	<link rel="stylesheet" href="игры.css">
	<title>любимые игры</title>
</head>
<body>
	<table>
		<tr>
			<td>anuken</td>
			<td>rob tob</td>
			<td>relogic</td>
			<td>team17</td>
		</tr>
		<tr>
			<td>mindustry</td>
			<td>geometry dash</td>
			<td>terraria</td>
			<td>the escapists 2</td>
		</tr>
</body>
</html>

CSS:
table{
	border: 2px solid black; text-align: center;
}
td{
	border: 2px solid black; text-align: center;
}

10й проект (тестсайт(мой первей код)):
HTML:
<!DOCTYPE html>
<head>
	<title>ТЕСТОВЫЙ САЙТ</title>
</head>
<html>
<body>
	<div id="why">
		<h1 style="color: darkorange; font-size: 27px;">почему коты стали моими любимыми животнами?
		<p><img src=C:\Users\GoidaPK\Documents\котсмотрит.png></p>
		</h1>
	</div>
	<ul>
		<li><a href="#fat">1 пункт</a></li>
		<li><a href="#eat">2 пункт</a></li>
		<li><a href="#sleap">3 пункт</a></li>
		<li><a href="#auch">4 пункт</a></li>
		<li><a href="#evil">5 пункт</a></li>
	</ul>
	<div id="fat">
		<h1>
	<li style="front-sixe: 18px;">они пушистые</li>
	<li style="front-sixe: 18px;"> <img src=C:\Users\GoidaPK\Documents\пушистыйкот.png></li>
	<li><a href="#why">хаб</a></li>
		</h1>
	</div>
	<div id="eat">
		<h1>
	<li style="front-sixe: 18px;">мало едят</li>
	<li style="front-sixe: 18px;"> <img src=C:\Users\GoidaPK\Documents\которкестр.png></li>
	<li><a href="#why">хаб</a></li>
		</h1>
	</div>
	<div id="sleap">
		<h1>
	<li style="front-sixe: 18px;">спят</li>
	<li style="front-sixe: 18px;"> <img src=C:\Users\GoidaPK\Documents\котспит.png></li>
	<li><a href="#why">хаб</a></li>
		</h1>
	</div>
	<div id="auch">
		<h1>
	<li style="front-sixe: 18px;">их можно гладить (но не всех)</li>
	<li style="front-sixe: 18px;"> <img src=C:\Users\GoidaPK\Documents\котзлой.png></li>
	<li><a href="#why">хаб</a></li>
		</h1>
	</div>
	<div id="evil">
		<h1>
	<li style="front-sixe: 18px;">они самые мирные существа на земле</li>
	<li style="front-sixe: 18px;"> <img src=C:\Users\GoidaPK\Documents\котвласть.png></li>
	<li><a href="#why">хаб</a></li>
		</h1>
	</div>
</body>
</html>

картинки были потеряны

11й проект (хедер):
HTML:
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" type="text/css" href="хедер_цвет.css">
	<title>хедер</title>
</head>
<body>
	<header>
		<h1>хедер</h1>

	<nav>
		<ul>
			<li>
				<a href="хаб">хаб</a>
			</li>
			<li>
				<a  href="https://youtu.be/dQw4w9WgXcQ?t=1">о нас</a>
			</li>
		</ul>
	</nav>

	<div>
		<h1>			
			<a href="https://youtu.be/dQw4w9WgXcQ?t=1">
				<button class="red">ссылка</button>
			</a>
		</h1>
	</div>
		
	<div class="section">
		<h2><img src=https://img5tv.cdnvideo.ru/webp/shared/files/202306/1_1720501.jpg></h2>
	</div>

	</header>
</body>
</html>

CSS:
h1{
	color: green;
}
.red{
	background-color: darkred;
	color: red;
	padding: 10px;
	border: none;
	cursor: pointer;
}
