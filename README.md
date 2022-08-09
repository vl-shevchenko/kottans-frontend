# kottans-frontend

### General
- [x] 0. Git Basics
- [x] 1. Linux CLI and Networking
- [x] 2. Git Collaboration

### Front-End Basics
- [x] 3. Intro to HTML & CSS
- [ ] 4. Responsive Web Design
- [ ] 5. HTML & CSS Practice
- [ ] 6. JavaScript Basics
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
  <details>
  <summary>List</summary>
  
  - [ ] 1. Responsive web design basics
  - [ ] 2. FLEXBOX. Вчимося верстати на флексах
  - [ ] 3. Flexbox Froggy - гра для закріплення
  - [ ] 4. CSS Grid Layout
  - [ ] 5. Grid Garden - гра для закріплення
  
  </details>
 
  `viewport` - Метатег viewport дает браузеру инструкции по управлению размерами и масштабированием страницы. <br>
  `width=device-width` - Значение метатега viewport width=device-width предписывает странице соответствовать ширине экрана в аппаратно-независимых пикселях. <br>
  `initial-scale=1` - предписывает браузерам устанавливать соотношение 1:1 между пикселями CSS и аппаратно-независимыми пикселями, независимо от ориентации устройства, что позволяет странице использовать всю ширину альбомной ориентации. <br>
  ```
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
   `align-content` отвечает за расстояние между рядами, в то время как `align-items` отвечает за то, как элементы в целом будут выровнены в контейнере. Когда только один ряд, `align-content` ни на что не влияет.
  <br>
  
