# fullstack-dev-exercises

## Exercises for lecture #3 Каскадні стилі сторінок (CSS)


1. Відредагуйте файл index.html
	- В розділі footer створіть section з атрибутом class="footer-social"
	- В середині цієї секції розмістіть елемент ul з атрибутом class="list-unstyled"
	- В середині ul розмістіть елементи li, кожний з яких має містити посилання на одну з соціальних мереж - facebook, twitter, github, linkedin, youtube, instagram.
	- Перегляньте документацію для font-awesome, знайдіть іконки відповідних соц-мереж та вставте їх як текст посилань


2. Відредагуйте файл css/main.css
	- визначити для усіх елементів h1, h2, h3 на веб-сторінці властивість колір тексту - сірий. 
	- визначити для елемента з ідентифікатором main властивість color: #e60202;.
	- визначити для елемента з класом h2 властивість color: червоний.
	- встановити для елемента з класом heading колір тексту у зелений.

3. Відвідайте веб-сайт Google Fonts https://fonts.google.com/.
знайдіть шрифт Roboto, додайте шрифт «Roboto» за допомогою посилання на сторінку index.html.


4. базовий розмір шрифта для кореневого елемента = 100%
	- визначити розмір шрифта для body, що успадковує розмір шрифта кореневого елемента, збільшений на 40 відсотків

	- визначити розмір шрифта для h1, що успадковує розмір шрифта кореневого елемента, збільшений на 140 відсотків

5. Додайте до сторінки index.html наступну розмітку
```html
	<div>
	<span>Outer <span>inner</span> outer</span>
	</div>
```
	- Припустімо, що розмір шрифту для body встановлено на 16 пікселів. 
	- Слова «Outer» відображається з розміром 25,6 пікселів, а слово «inner» — 40,96 пікселів.
	- Всередині файла css/main.css 
		- визначте властивсть font-size для div, вказавши значення в одиницях виміру em.
		- визначте властивсть font-size для span, вказавши значення в одиницях виміру em.


6. Додайте до сторінки index.html наступну розмітку
```html
 	<div>
        <strong>Outer <strong>inner</strong> outer</strong>
    </div>
```
	- Припустімо, що розмір шрифту для body встановлено на 16 пікселів. 
	- Всередині файла css/main.css визначте властивсть font-size для strong так, щоб всі слова мали однаковий відносний розмір, еквівалентний 25,6 пікселів.

7. Відредагувати файл css/main.css
	- Встановити властивості елемента body:
		- font-family: Roboto
		- font-size: 1rem
	- Встановити властивість font-weight: 700 для елементів h1, h2, h3
	- Встановити властивість font-size: 1.45rem для елемента h1
	- Встановити властивість font-size: 1.3rem для елемента h2
	- Визначити клас .list-unstyled з властивістю list-style: none
	- Визначити клас .footer-social


8. Відредагуйте файл css/main.css 
	- Виконайте імпорт шрифтів font-awesomeза допомогою правила @import. 

9. Відредагуйте файл index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
	<link rel="shortcut icon" href="/favicon.ico" type="image/x-icon">

    <style>

    </style>

</head>

<body class="body">
    
    <h1>Gradient Text Glow</h1>

    <div class="percents">
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quis cum magnam quae adipisci minima illum porro eius ipsa rem. Sequi eaque facere necessitatibus fugiat rerum facilis reprehenderit numquam dignissimos itaque!
    </div>

    <div class="negative">
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quis cum magnam quae adipisci minima illum porro eius ipsa rem. Sequi eaque facere necessitatibus fugiat rerum facilis reprehenderit numquam dignissimos itaque!
    </div>

    <div class="radial">
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quis cum magnam quae adipisci minima illum porro eius ipsa rem. Sequi eaque facere necessitatibus fugiat rerum facilis reprehenderit numquam dignissimos itaque!
    </div>
</body>
</html>
```
- Встановити background для класу body як лінійний градієнт, що напрвлений вправо, та моє такі точки зупинки: 5%, 17%, 40%, 85%, 95%. Для кожної точки зупинки встановити колір, що змінюється від світлозеленго до темнозеленго. 

- Встановити background для класу negative як лінійний градієнт, що напрвлений вліво, та моє такі точки зупинки: -50%, -10%, 0%, 100%, 150%. Для кожної точки зупинки встановити колір, що змінюється від світлосинього до темносинього. 

- Встановити background для класу percents як лінійний градієнт, що напрвлений вниз, та моє такі точки зупинки: 2em, 4em, 8em, 16em, 32em, 64em, 128em. Для кожної точки зупинки встановити колір, що змінюється від світлозеленого до темнозеленого. 

- Встановити background для класу radial два радіальних градієнта з типом ellipse, перший з яких містить 2 кольори - помаранчевмй та прозорий і напрвлений вверх, а другий містить 2 кольори - червонмй та прозорий і напрвлений вниз. 
