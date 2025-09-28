# fullstack-dev-exercises

## Exercises for lecture #4 FlexBox

1. В середині exercises створіть піддирексторію lecture-04. В середині lecture-04 створіть файли index.html та css/main.css. 

## файл index.html:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="css/main.css">
  <title>Exercises for lecture #7</title>
</head>
<body>
  <nav class="nav">
    <span>Brand Name</span>
    <ul class="link-list">
      <li class="link"><a href="#">Home</a></li>
      <li class="link"><a href="#">Pricing</a></li>
      <li class="link"><a href="#">About</a></li>
      <li class="link"><a href="#">Contact</a></li>
    </ul>
  </nav>

    <h2>CSS Flex Property</h2>
    <div class="wrapper">
        <div class="item item-blue">CSS</div>
        <div class="item item-orange">Flex</div>
        <div class="item item-green">Property</div>
    </div>

    <h2>CSS flex-grow Property</h2>
    <div class="grow-wrapper">
        <div class="item item-blue">Blue</div>
        <div class="item item-orange">Orange</div>
        <div class="item item-green">Green</div>
    </div>

      <ul role="list" class="flexbox">
  <li class="card">
    <h3>Lorem, ipsum.</h3>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
  </li>
  <li class="card">
    <h3>Minus, pariatur?</h3>
    <p>Veritatis optio illum possimus eveniet exercitationem perferendis ad?</p>
  </li>
  <li class="card">
    <h3>Iste, assumenda!</h3>
    <p>Esse minima in maiores similique unde eaque nostrum!</p>
  </li>

  <li class="card">
    <h3>Lorem, ipsum.</h3>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
  </li>
  <li class="card">
    <h3>Minus, pariatur?</h3>
    <p>Veritatis optio illum possimus eveniet exercitationem perferendis ad?</p>
  </li>
  <li class="card">
    <h3>Iste, assumenda!</h3>
    <p>Esse minima in maiores similique unde eaque nostrum!</p>
  </li>
</ul>

</body>
</html>

```

## файл css/main.css:

```css
* {
  box-sizing: border-box;
}

body {
  margin: 0;
}

.nav {
  background-color: #333;
  color: white;
  display: flex;
  
  padding: 0 .5rem;
}

.link-list {
  display: flex;
  margin: 0;
  list-style: none;
}

.link {
  padding: .5rem;
}

.link:hover {
  background-color: #777;
}

.link a {
  color: inherit;
  text-decoration: none;
}

 .wrapper, .grow-wrapper {
    display: flex;
    flex-wrap: wrap;
    width: 700px;
    }

  .item-blue {
      background-color: blue;
  }
  .item-orange {
      background-color:orange;  
  }
  .item-green {
      background-color:green;
  }

  .item {
      color: white;
      width: 100px;
  }

  .flexbox {
  --min: 30ch;

  display: flex;
  flex-wrap: wrap;

  gap: 1rem;
}
```

    - Вирівняйте елементи навігаційної панелі nav по вертикалі так, щоб вони мали однакову відстань зверху та знизу.
    - Вирівняйте елементи навігаційної панелі nav по глризонталі так, щоб Brand Name розташувався зліва, а пункти меню - справа. 
    - розподілити простір між елементами flex в середині контейнера wrapper так, щоб вони мали однакову ширину та заповнювали весь доступний простір.
    - Встановіть для елемена blue в контейнері grow-wrapper фактор зростання 3
    - Встановіть для елемена green в контейнері grow-wrapper фактор зростання 1
    - Налаштуйте едементи з класом card так, щоб вони пропорційно ділили між собою весь доступний простір та мали базовий розмір, визначений змінною --min.

