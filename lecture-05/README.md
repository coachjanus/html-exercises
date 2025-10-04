# fullstack-dev-exercises

## Exercises for lecture #5 Модуль Grid

1. В середині exercises створіть піддирексторію lecture-05. В середині lecture-05 створіть файли index.html та css/main.css. 

## файл index.html:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="css/main.css">
  <title>Exercises for lecture #8</title>
</head>
<body>
  <header>
    <h1>CSS Grid Layout</h1>
  </header>

  <article class="grid1">
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>7</div>
    <div>8</div>
    <div>9</div>
    <div>10</div>
    <div>11</div>
    <div>12</div>
  </article>

  <article class="grid2">
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>7</div>
    <div>8</div>
    <div>9</div>
    <div>10</div>
    <div>11</div>
    <div>12</div>
  </article>

<article class="grid3">
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>7</div>
    <div>8</div>
    <div>9</div>
    <div>10</div>
    <div>11</div>
    <div>12</div>
  </article>

  <article class="grid4">
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>7</div>
    <div>8</div>
    <div>9</div>
    <div>10</div>
    <div>11</div>
    <div>12</div>
  </article>

  <article class="grid5">
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>7</div>
    <div>8</div>
    <div>9</div>
    <div>10</div>
    <div>11</div>
    <div>12</div>
  </article>
  
  <article class="grid6">
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>7</div>
    <div>8</div>
    <div>9</div>
    <div>10</div>
    <div>11</div>
    <div>12</div>
  </article>

  <article class="grid7">
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>7</div>
    <div>8</div>
    <div>9</div>
    <div>10</div>
    <div>11</div>
    <div>12</div>
  </article>

  <article class="grid8">
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>7</div>
    <div>8</div>
    <div>9</div>
    <div>10</div>
    <div>11</div>
    <div>12</div>
  </article>

  <article class="grid9">
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>7</div>
    <div>8</div>
    <div>9</div>
    <div>10</div>
    <div>11</div>
    <div>12</div>
  </article>

  <article class="grid10">
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>7</div>
    <div>8</div>
    <div>9</div>
    <div>10</div>
    <div>11</div>
    <div>12</div>
  </article>
  <article class="grid11">
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>7</div>
    <div>8</div>
    <div>9</div>
    <div>10</div>
    <div>11</div>
    <div>12</div>
  </article>
  <article class="grid12">
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>7</div>
    <div>8</div>
    <div>9</div>
    <div>10</div>
    <div>11</div>
    <div>12</div>
  </article>
  <article class="grid13">
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>7</div>
    <div>8</div>
    <div>9</div>
    <div>10</div>
    <div>11</div>
    <div>12</div>
  </article>
</body>
</html>

```

## файл css/main.css:

```css

* {
  box-sizing: border-box;
}
      
article div:nth-of-type(1) {
    background-color: #c9316b;
}

article div:nth-of-type(2) {
    background-color: #c9319e;
}
article div:nth-of-type(3) {
    background-color: #c231c9;
}
article div:nth-of-type(4) {
    background-color: #8f31c9;
}
article div:nth-of-type(5) {
    background-color: #5c31c9;
}
article div:nth-of-type(6) {
    background-color: #3138c9;
}
article div:nth-of-type(7) {
    background-color: #316bc9;
}
article div:nth-of-type(8) {
    background-color: #319ec9;
}
article div:nth-of-type(9) {
    background-color: #31c9c2;
}

article div:nth-of-type(10) {
    background-color: #31c98f;
}

article div:nth-of-type(11) {
    background-color: #31c95c;
}

article div:nth-of-type(12) {
    background-color: #38c931;
}


article {
  margin: 2vw 0;
}
            
article div {
  color: #fff;
  padding: 5vh;
}
```

    - створити grid-контейнер grid1 з трьох стовпців шириною 15%, 60%, 25%
    - створити grid-контейнер grid2 з трьох рядків висотою 295px 1fr 270px
    - створити grid-контейнер grid3 з трьох рядків висотою 90px 300px 1fr і чотирьох стовпців однакової ширини
    - створити grid-контейнер grid4 з чотирьох стовпців однакової ширини та розмістити стовпці в центрі контейнера
    - створити grid-контейнер grid5 з чотирьох стовпців однакової ширини, що дорівнює 50px та розташуйте стовпці в кінці рядка grid-контейнера
    - створити grid-контейнер grid6 з чотирьох стовпців однакової ширини, що дорівнює 50px. розташуйте стовпці, встановивши рівномірну відстань між кожною парою стовпців
    - створити grid-контейнер grid7 з чотирьох стовпців однакової ширини, що дорівнює 50px. розташуйте стовпці, встановивши однакові відстані для кожної сторони стовпців
    - створити grid-контейнер grid8 з чотирьох стовпців однакової ширини, що дорівнює 50px. призначте рівномірні відстані до обох кінців grid-контейнера та між стовпцями
    - створити grid-контейнер grid9 з 2-х стовпців однакової ширини. встановіть вирівнювання за замовчуванням для всіх елементів grid-контейнер.
    - створити grid-контейнер grid10 з 2-х стовпців однакової ширини. встановіть вирівнювання у напрямку до початкового краю grid-контейнер для всіх елементів.
    - створити grid-контейнер grid11 з 2-х стовпців однакової ширини. встановіть вирівнювання у напрямку центру grid-контейнер для всіх елементів.
    - створити grid-контейнер grid12 з 2-х стовпців однакової ширини. встановіть рівномірну відстань між кожною парою рядків grid-контейнера.
    - створити grid-контейнер grid13 з 2-х стовпців однакової ширини. встановіть рівномірну відстань до обох кінців контейнера сітки та між її рядками.

