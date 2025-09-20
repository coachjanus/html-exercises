# fullstack-dev-exercises

## Exercises for lecture #2

1. Створіть мінімальний сайт, що складається з 4 сторінок:

	1. Головна - index.html
	2. Про нас - about.html
	3. Каталог - catalog.html
	4. Контакти - contact.html

Кожна сторінка повинна мати такі розділи

	- nav
	- header
	- main
	- footer

- Розділ nav повинен містити відносні посилання нв сторінки сайта, наприклад <a href="/">Home</a>
- Розділ header повинен містити тег загодовку 1-го ріаня.
- Розділ footer повинен містити абсолютеі посилання нв зовнішні сторінки, наприклад: <a href="https://www.google.com">Google</a>, та відкривати відповідний документ у новому вікні.


2. Створити файл css/main.css
	- Перейти до кореня персонального сайта
	- Створити файли css/main.css та css/base.css
	- Відредагувати файл index.html
		1. Підключити css/main.css за допомогою тега link
		2. Підключити css/base.css за допомогою правила @import


3. Відредагувати файл css/base.css
	- Визначити у глобальній області видимості змінну:
    	--accentColorMuted: hsl(300, 40%, 40%);
	- Встановити, за допомогою цієї змінної властивість color для елемента a

4. Відредагувати розділ footer
```html

<footer>
  <!-- створити тут секцію -->
  	<!-- створити тут div -->
      <h2>About</h2>
	  <!-- 
	  створити тут невпорядкований список з такмсм елементами 
	  	<a href="#">Services</a>
        <a href="#">Portfolio</a>
        <a href="#">Pricing</a>
        <a href="#">Customers</a>
        <a href="#">Careers</a>
	  -->
	
	<!-- створити тут div -->
      <h2>Resources</h2>
	  <!-- 
	  створити тут невпорядкований список з такмсм елементами 
	  	<a href="#">Docs</a>
        <a href="#">Blog</a>
        <a href="#">eBooks</a>
        <a href="#">Webinars</a>
	  -->

	<!-- створити тут div -->
      <h2>Contact</h2>
	  <!-- 
	  створити тут невпорядкований список з такмсм елементами 
	  	<a href="#">Help</a>
        <a href="#">Sales</a>
        <a href="#">Advertise</a>
	  -->

  
  <!-- Footer legal -->
  <!-- створити тут section -->
  <!-- 
	  створити тут невпорядкований список з такмсм елементами 
	  	<a href="#">Terms &amp; Conditions</a>
        <a href="#">Privacy Policy</a>
        &copy; 2024 Copyright Shopaholic Inc.
	  -->
</footer>
```

Завантажте створений сайт у власний репозиторій на https://github.com. 

