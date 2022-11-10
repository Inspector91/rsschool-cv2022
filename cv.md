# Bogdanov Sergei

![pfoto](/rsschool-cv2022/img/photo.JPG)

***

## Contact information:
Phone: +7 951 000 00 00
E-mail: BogdanovSA91@gmail.com
Telegram: @InspectorMRSK

***
## About myself:
I work as an design engineer and study the fron-end.

***

## Skills
+ CSS3
+ HTML5
+ GitHub
+ Markdowm
+ VS Code
+ JavaScript in progress...

***
## Education  
+ Omsk Technical University, Electrical Engineer  
+ Omsk Technical University, Master in Electrical Power Engineering and Electrical Engineering

***
### Courses
+ RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)  

***
## Code example: 
### CSS
```
@font-face {
    font-family: Inter_bold;
     src: url("assets/fonts/Inter-VariableFont_slnt,wght.ttf");
     font-weight: 700;
   }
html {
    scroll-behavior: smooth; 
  }
.body {
    background-color: #000;
    margin: 0;
  }
```
### HTML
```
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>portfolio</title>
    <link rel="stylesheet" href="./style.css">
    <link rel="icon" href="./assets/img/camera.ico">
    <script src="./index.js"></script>
</head>
```
### JavaScript
```
//Адаптивное меню
const hamburger = document.querySelector('.hamburger');
const menu = document.querySelector('.menu');

function toggleMenu() {
  hamburger.classList.toggle('open');
  menu.classList.toggle('open');
}
hamburger.addEventListener('click', toggleMenu);

function closeMenu(event) {
  if (event.target.classList.contains('nav-link')) {
    menu.classList.remove('open');
    hamburger.classList.remove('open');
  }
}

menu.addEventListener('click', closeMenu);
```

***
## Projects  
[Portfolio Task](https://rolling-scopes-school.github.io/inspector91-JSFEPRESCHOOL/portfolio/)

***
## Languages  
+ English - *Intermediant* (according to the online test at [www.efset.org](www.efset.org))
+ Russian - *Native*
