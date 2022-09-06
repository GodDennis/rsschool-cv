# Denis Podreckiy
## Contact
**Phone number** - *+375 25 9991417*
**Email** - *denpodreckiy@mail.ru*
**Discord** - *Ghoul#3385*
## Briefly About Myself:
Some month ago i started learning on front-end developer and in future
i wanna become a junior front-end developer.
As well i have a interest to learning more new things in this area.
## Skills
HTML5, CSS3
JavaScript Basic
Git, GitHub
VS Code
Figma for developer
Zeplin
Avocode
## Languages
English - A2
Belarussian - Native
Russian - Native
## Code Example
Slider
```
let slider = document.querySelector('.flexblock');
let img = document.querySelectorAll('.flexblock div');
let dot = document.querySelectorAll('.dot');
let offset = 0;
let netxBtn = document.querySelector('.next')
netxBtn.addEventListener('click', function () {
    offset -= 59.5;
    if (offset < -59.5) {
        offset = 59.5;
    }
    slider.style.transform = 'translate(' + offset + '%)';
    slider.style.transition = "transform 1s linear";
})
let prevBtn = document.querySelector('.prev')
prevBtn.addEventListener('click', function () {
    offset -= 59.5;
    if (offset < -59.5) {
        offset = 59.5;
    }
    slider.style.transform = 'translate(' + -offset + '%)';
    slider.style.transition = "transform 1s linear";
})
```
