 Имя и фамилия
        Контакты для связи
        Краткая информация о себе (ваша цель и приоритеты, подчеркните свои сильные стороны, расскажите о своём опыте работы, если опыта работы нет, расскажите о своём стремлении и способности быстро учиться и узнавать новое)
        Навыки (языки программирования, фреймворки, методологии, системы контроля версий и инструменты разработки, которыми вы владеете)
        Примеры кода *
        Опыт работы. Junior Dev может указать пройденные курсы и тренинги, перечислить учебные проекты, или проекты, выполненные на фрилансе с указанием использованных навыков и ссылками на исходный код.**
        Образование (включая курсы, семинары, лекции, онлайн-обучение)
        Английский язык (уровень английского языка, если была языковая практика, расскажите о ней)
        
   # Maxim Shepelev
   ## 07.07.1996
        
   ## _phone: **+7(938)148-61-01**_
   ## _email: **torchlight15@gmail.com**_
   
   ## _About myself_
   My name is Max, I'm 24 years old and in last year I've finished an university **(Don State Technical University)**. My profession is architector and desighner, but I don't really like it. So after university I have deсided to start learn programming. 
   I have an American Dream and would like to change the world! I would really like to create any cool projects, which will change whe world. For example I like ideas about AI like a Ultron in a **Avengeres** movie. I worked only like an a waiter and I have some soft skills for communicate to different people. I am an a stress tolerance and can work in multitasking mode. I like read books and I readd a lot. I can quickly learn and learn new things. Analyze the information I received.
   ## _Skills_
   ### I use:
   * Languages and technologies:
     * HTML5
     * CSS3
     * JavaScript
     * Python
       *** Django
     * Git
      * GitHub
               
   * Methodology:
      * BEM
      * AGILE
     
   ## _Code examples:_
My study project  calculator (with no tests and try_catch)


  ## _Work experience_
I dont have an production experience with IT.

  ## _Education_
I've finished some online courses:
* Web Development, by https://stepik.org
* Java Script from 0, by [IT-KAMASUTRA](https://www.youtube.com/channel/UCTW0FUhT0m-Bqg2trTbSs0g)
* Web Developer, by skillbox

I've read some books with programming and did code from it:
* Head Firt. HTML5 Programming, by Eric Freeman
* Learn HTML, XHTML and CSS, by Eric Freeman
* A byte of Python, by Swaroop C.H.
* JavaScript for Kids: A Playful Introduction to Programming, by Nick Morgan 
* Clean code, by Robert Martin

## _English language_

I got english courses from 2016 till the 2018 and in this time I had B1. But next time I have not used english in my life, so now I have A2 and It's **really** difficult to speak english when you don't have anought practice. I try to watch movies in english and read books now.
        
```
//study calculator with UI (HTML, CSS)
window.onload = init;
const allButtons = document.querySelectorAll('button');
let isMouseDown = false;

// for clear field after = or if field is empty
let is_equal = false;

// Remove focus on click
allButtons.forEach(function (el) {

  el.addEventListener('mousedown', () => (isMouseDown = true));

  el.addEventListener('mouseup', () => (isMouseDown = false));

  el.addEventListener('focus', () => {
    if (isMouseDown) {
      el.blur();
    }
  });
});

// Clear output field when page reload.
function init() {
  let startField = document.getElementById("my_calc__text_area");
  startField.value = "";
};

// Outputs clicked signs.
function insert(num) {
  let output = document.form.textview.value;
  if (output == "" || is_equal) {
    document.form.textview.value = num;
    is_equal = false;
  } else {
    document.form.textview.value = document.form.textview.value + num;
  }
};

// Clear field when click.
function clean() {
  document.form.textview.value = "";
};

// Delete last sign (like backspace).
function back() {
  let output = document.form.textview.value;
  if (output) {
    document.form.textview.value = output.substring(0, output.length - 1);
  }
};

// Calculates and output result with eval().
function result() {
  let output = document.form.textview.value;
  if (output) {
    document.form.textview.value += "=" + eval(output);
    is_equal = true;
  }
  is_equal = true;
};

// Print something you want.
function something() {
  let text = "Quiet... Don't click it!";
  document.form.textview.value = text;
};
```

  


        
