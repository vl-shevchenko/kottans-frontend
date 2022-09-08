# kottans-frontend

### General
- [x] 0. Git Basics
- [x] 1. Linux CLI and Networking
- [x] 2. Git Collaboration

### Front-End Basics
- [x] 3. Intro to HTML & CSS
- [x] 4. Responsive Web Design
- [x] 5. HTML & CSS Practice
- [x] 6. JavaScript Basics
- [ ] 7. Document Object Model - practice

### Advanced Topics
- [ ] 8. Building a Tiny JS World (pre-OOP) - practice
- [ ] 9. Object oriented JS - practice
- [ ] 10. OOP exercise - practice
- [ ] 11. Offline Web Applications - optional
- [ ] 12. Memory pair game — real project!
- [ ] 13. Website Performance Optimization - optional
- [ ] 14. Friends App - real project!



## Git, GitHub, git flow 

<details>
  <summary>Git commands</summary>
  
  `git commit -a` Stages files automatically <br>
  `git log -p` Produces patch text <br>
  `git show` Shows various objects <br>
  `git diff` Is similar to the Linux `diff` command, and can show the differences in various commits <br>
  `git diff --staged` An alias to --cached, this will show all staged files compared to the named commit <br>
  `git add -p` Allows a user to interactively review patches to add to the current commit <br>
  `git mv` Similar to the Linux `mv` command, this moves a file <br>
  `git rm` Similar to the Linux `rm` command, this deletes, or removes a file <br>
  `git revert` A new commit is created with inverse changes. This cancels previous changes instead of making it as though the original commit never happened <br>
  `git checkout -b NAME` Creates a new branch and switches to it <br>
  `git branch` Used to manage branches <br>
  `git branch <name>` Creates the branch <br>
  `git branch -d <name>` Deletes the branch <br>
  `git branch -D <name>` Forcibly deletes the branch <br>
  `git checkout <branch>` Switches to a branch <br>
  `git checkout -b <branch>` Creates a new branch and switches to it <br>
  `git merge <branch>` Merge joins branches together <br>
  `git merge --abort` If there are merge conflicts (meaning files are incompatible), --abort can be used to abort the merge action <br>
  `git log --graph --oneline` This shows a summarized view of the commit history for a repo <br>
  `git clone URL` Git clone is used to clone a remote repository into a local workspace <br>
  `git push` Git push is used to push commits from your local repo to a remote repo <br>
  `git pull` Git pull is used to fetch the newest updates from a remote repository <br>
  
</details>

1. Ознайомився з Git та GitHub
2. Зробив pull-request



## Linux CLI, and HTTP

1. Linux Survival (4 modules)

<details>
  <summary>Screenshot</summary>
  
  ![Screenshot](https://github.com/vl-shevchenko/kottans-frontend/blob/main/quiz_linux/linux1.JPG)
  ![Screenshot](https://github.com/vl-shevchenko/kottans-frontend/blob/main/quiz_linux/linux2.JPG)
  ![Screenshot](https://github.com/vl-shevchenko/kottans-frontend/blob/main/quiz_linux/linux3.JPG)
  ![Screenshot](https://github.com/vl-shevchenko/kottans-frontend/blob/main/quiz_linux/linux4.JPG)
  
 </details>
  

2. HTTP: Протокол, який повинен розуміти кожний веб-розробник - Частина 1
3. HTTP: Протокол, який повинен розуміти кожний веб-розробник - Частина 2

## Git Collaboration

1. Прослухаd тижні 3 і 4 курсу Introduction to Git and GitHub
2. Пройijd наступні рівні learngitbranching.js.org: <br>
        - Основи: Їдемо далі, Переміщуємо роботу туди-сюди <br>
        - Віддалені репозиторії: Через origin – до зірок. Прогресивне використання Git Remotes <br>
        
<details>
  <summary>Screenshot</summary>
  
  ![Screenshot](https://github.com/vl-shevchenko/kottans-frontend/blob/main/task_git_collaboration/Foundations.JPG)
  ![Screenshot](https://github.com/vl-shevchenko/kottans-frontend/blob/main/task_git_collaboration/origin_pushandpull.JPG)
  
 </details>  
  
## Intro to HTML and CSS
 
 1. Intro to HTML & CSS: 
  <details>
  <summary>Screenshot</summary>
  
  ![Screenshot](https://github.com/vl-shevchenko/kottans-frontend/blob/main/task_html_css_intro/week1.JPG)
  ![Screenshot](https://github.com/vl-shevchenko/kottans-frontend/blob/main/task_html_css_intro/week2.jpg)
  
 </details> 
 
 2. Learn HTML(Eng)
  <details>
  <summary>Screenshot</summary>
  
  ![Screenshot](https://github.com/vl-shevchenko/kottans-frontend/blob/main/task_html_css_intro/html.jpg)
  
 </details> 
 
  3. Learn CSS(Eng)
  <details>
  <summary>Screenshot</summary>
  
  ![Screenshot](https://github.com/vl-shevchenko/kottans-frontend/blob/main/task_html_css_intro/css.jpg)
  
 </details> 
 
 ## Responsive Web Design
    
  - [x] 1. Responsive web design basics
  - [x] 2. FLEXBOX. Вчимося верстати на флексах
  - [x] 3. Flexbox Froggy - гра для закріплення
    
  <details>
  <summary>Screenshot</summary>
  
  ![Screenshot](https://github.com/vl-shevchenko/kottans-frontend/blob/main/task_responsive_web_design/flexBox_froggy.jpg)
  
  </details>
    
  - [x] 4. CSS Grid Layout
  - [x] 5. Grid Garden - гра для закріплення
   
   <details>
  <summary>Screenshot</summary>
  
  ![Screenshot](https://github.com/vl-shevchenko/kottans-frontend/blob/main/task_responsive_web_design/grid_garden.jpg)
  
 </details> 
  
 
 <details>
  <summary>FlexBox</summary>
 
  `viewport` - Метатег viewport дает браузеру инструкции по управлению размерами и масштабированием страницы. <br>
  `width=device-width` - Значение метатега viewport width=device-width предписывает странице соответствовать ширине экрана в аппаратно-независимых пикселях. <br>
  `initial-scale=1` - предписывает браузерам устанавливать соотношение 1:1 между пикселями CSS и аппаратно-независимыми пикселями, независимо от ориентации устройства, что позволяет странице использовать всю ширину альбомной ориентации. <br>
  ```html
  <!DOCTYPE html>
<html lang="en">
  <head>
    …
    <meta name="viewport" content="width=device-width, initial-scale=1">
    …
  </head>
  …
  ```
  **justify-content** - выравнивает элементы горизонтально и принимает следующие значения:<br>
  `flex-start` Элементы выравниваются по левой стороне контейнера.<br>
  `flex-end` Элементы выравниваются по правой стороне контейнера.<br>
  `center` Элементы выравниваются по центру контейнера.<br>
  `space-between` Элементы отображаются с одинаковыми отступами между ними.<br>
  `space-around` Элементы отображаются с одинаковыми отступами вокруг них.<br>
  `stretch` Ряды растягиваются, чтоб заполнить контейнер равномерно.<br>
  <br>
  **align-items** - Это CSS свойство выравнивает элементы вертикально и принимает следующие значения:<br>
  `flex-start` Элементы выравниваются по верхнему краю контейнера.<br>
  `flex-end` Элементы выравниваются по нижнему краю контейнера.<br>
  `center` Элементы выравниваются вертикально по центру контейнера.<br>
  `baseline` Элементы отображаются на базовой линии контейнера.<br>
  `stretch` Элементы растягиваются, чтоб заполнить контейнер.<br>
  <br>
  **flex-direction** то CSS свойство задает направление, в котором будут расположены элементы в контейнере, и принимает следующие значения:<br>
  `row` элементы размещаются по направлению текста.<br>
  `row-reverse` элементы отображаются в обратном порядке к направлению текста.<br>
  `column` элементы располагаются сверху вниз.<br>
  `column-reverse` элементы располагаются снизу вверх.<br>
  <br>
  `order` изменениe порядка отображения элементов в контейнере<br>
  <br>
  **flex-wrap** переносит в след ряд<br>
  `nowrap` Размеры элементов устанавливаются автоматически, чтоб они поместились в один ряд.<br>
  `wrap` Элементы автоматически переносятся на новую строку.<br>
  `wrap-reverse` Элементы автоматически переносятся на новую строку, но строки расположены в обратном порядке.<br>
  <br>
  **flex-flow** = `flex-direction` + `flex-wrap`<br>
  <br>
   >`align-content` отвечает за расстояние между рядами, в то время как `align-items` отвечает за то, как элементы в целом будут выровнены в контейнере. Когда только один ряд, `align-content` ни на что не влияет.
  <br>
  
  </details>
  
  
  ## HTML-CSS-Popup
Цікаве завдання. Отримав задоволення від практики.<br>
Довелося багато інформації перечитати. Найпроблемніший момент був з `<input>` :octocat:

[Demo](https://vl-shevchenko.github.io/popup/) |
[Code base](https://github.com/vl-shevchenko/popup)

## JavaScript Basics

<details>
  <summary>JavaScript</summary>
  
JavaScript надає вісім різних типів data: `undefined`, `null`, `boolean`, `string`, `symbol`, `bigint`, `number` та `object`.<br> 
Основні типи:<br>
`string` - рядковий тип. Записується в подвійних або одинарних кавичках.<br>
`number` - числовий тип. Пишимо без кавичок. Використовуємо цей тип тоді, коли хочемо з даними пряцювати як з числами (виконувати математичні завдання).<br>
`boolean` - логічний тип даних. Має тільки два можливих значення - **true**(1) i **false**(0). Значення true або false пишуться без кавичок.  <br>
<br>
`var` - оголошення змінної (старий варіант)
```js
var ourName;
```
Сучасний варіант `const` або `let`.<br>
`const` - не змінюється протягом роботи програми (скрипту). Значення є константою.<br>
`let` - може змінюватися протягом роботи програми (скрипту).<br>
<br>
Pозробники пишуть назву ідентифікаторів незмінних значень великими літерами,<br> 
а назви змінних значень (об'єктів та масивів) — маленькими літерами або через camelCase.<br>
```js
i++;
є еквівалентом

i = i + 1;
```
```js
i--;
дорівнює

i = i - 1;
```
`+=`  оператор, якbq виконує математичні дії та присвоєння за один крок.
```js
let myVar = 1;
myVar += 5;
console.log(myVar);
У консолі відображатиметься значення `6`.
```
```js
Код	При виведенні буде
\'	одинарні лапки
\"	подвійні лапки
\\	зворотня коса риска
\n	новий рядок
\r	повернення каретки
\t	вкладка
\b	границі слова
\f	розрив сторінки
```
 Pядки i масиви використовують індексування на основі нуля, тому перший елемент у масиві має індекс 0.<br>
 ```js
 Шаблонные строки (обязательно используем обратные кавычки):
 let userName = "Джон";
 let greeeting = `Привет, ${userName}, как дела?`;
 console.log(greeeting);
 ```
 **Умова:**
 ```js
 if (/*умова*/){
 /*код, який буде виконано, якщо умова правильна*/
 } else {
 /*код, який буде виконано, якщо умова НЕ правильна*/
 }
 ```
 **Приклад:**
 ```js
 let x = 1;
 let y = 5;
 
 if (x > y) {
 console.log("X більше Y");
 } else if (x === y) {    //для порівняння використовуємо подвійне або потрійне дорівнює
 console.log("X дорівнює Y");
 } else (x < y) {
 console.log("X менше Y");
 }
 ```
 Массив (другим словом коллекция) - для хранения элементов, которые связаны между собой по смыслу.
 ```js
 const fruits = ["Яблоко", "Груша", "Слива", "Апельсин"];
 ```
 **Цикл for**
 ```js
 for (let i = 0; i < 10; i++) {
    console.log('i = ' + i);
 }
 ```
 **Пример использования цикла for**
 ```js
 const fruits = ["Яблоко", "Груша", "Слива"];
 for (let i = 0; i < 3; i++) {      //или вместо числа 3 подставляэм `fruits.length` (`.length` - показывает количество элементов в массиве)
    console.log(fruits[i]);
 }
 ```
 **Обход массивов с помощью метода .forEach()**
 ```js
 const fruits = ["Яблоко", "Груша", "Слива", "Апельсин"];
 fruits.forEach(function(item, index){
      console.log(`Элемент ${item} имеет индекс ${index}`);
 })
 ```
 **Function:**
 ```js
 function calculateSum(x, y) {
    let result = x + y;
    return result;
 }
 let answer = calculateSum(5, 10);
 console.log(answer);     //15
 ```
 Функції можна передавати як аргумент в інші функції. Приклад:
  ```js
 function calculateSum(x, y) {
    let result = x + y;
    return result;
 }
 let res = calculateSum(calculateSum(20, 10), calculateSum(30, 40));      //це спрацює, томущо є "return result;" у функції
 console.log(res); //100
 
 /*можна замість "let res =..." та "console.log(res);"
 написати однією строчкою:
 console.log(calculateSum(calculateSum(20, 10), calculateSum(30, 40)));*/
 ```

</details>

  <details>
  <summary>Basic JavaScript</summary>
  
  ![Screenshot](https://github.com/vl-shevchenko/kottans-frontend/blob/main/task_js_basics/Screenshot%202022-08-29%20131832.jpg)
  
 </details>
   <details>
  <summary>ES6 Challenges</summary>
  
  ![Screenshot](https://github.com/vl-shevchenko/kottans-frontend/blob/main/task_js_basics/ES6%20Challenges.jpg)
  
 </details>
    <details>
  <summary>Basic Data Structures</summary>
  
  ![Screenshot](https://github.com/vl-shevchenko/kottans-frontend/blob/main/task_js_basics/Basic%20Data%20Structures.jpg)
  
 </details>
     <details>
  <summary>Functional Programming</summary>
  
  ![Screenshot](https://github.com/vl-shevchenko/kottans-frontend/blob/main/task_js_basics/Functional%20Programming.jpg)
  
 </details>
      <details>
  <summary>Algorithm Scripting Challenges</summary>
  
  ![Screenshot](https://github.com/vl-shevchenko/kottans-frontend/blob/main/task_js_basics/Algorithm%20Scripting%20Challenges.jpg)
  
 </details>
 
 ## DOM

Більше дізнався про CSS, JS...:octocat:

[Demo](https://vl-shevchenko.github.io/dom/) |
[Code base](https://github.com/vl-shevchenko/dom)
  
<details>
<summary>Algorithm Scripting Challenges12-18</summary>
  
  ![Screenshot](https://github.com/vl-shevchenko/kottans-frontend/blob/main/task_js_dom/Algorithm%20Scripting%20Challenges%2012-18.jpg)
  
 </details>
 
## Building a Tiny JS World
:octocat:

[Demo](https://vl-shevchenko.github.io/a-tiny-JS-world/) |
[Code base](https://github.com/vl-shevchenko/a-tiny-JS-world)

## OOP exercise

[Demo](https://vl-shevchenko.github.io/a-tiny-JS-world/) |
[Code base](https://github.com/vl-shevchenko/a-tiny-JS-world)
