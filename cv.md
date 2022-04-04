# __Roman Kadkin__

### Frontend Developer

## __Contacts__
- __Location:__ Saint-Petersburg, Russia
- __Phone:__ +7 921 637 65 07
- __Email:__ kadkin_roman@mail.ru
- __GitHub:__ [KadkinRoman](https://github.com/KadkinRoman/)

## __About Me__
I have experience in commercial development in C++ and C##.  
Now I want to become a web developer, so I began to actively study website development technologies.  
I learned the basics of java script, html and sss. Also created some simple websites.  
My task is to improve the skills of creating websites and achieve high results.

## __Skills__
- HTML
- CSS/SASS
- JavaScript
- Git
- BEM methodology
- Figma
- Editors: VSCode

## __Code Example__
Write a function that accepts a square matrix (N x N 2D array) and returns the determinant of the matrix.

```
function determinant(m) {

    if (m.length == 1) {
        return Number(m)
    }

    let det = 0;

    for (let i = 0; i < m.length; i++) {
        if (m.length > 2) {
            det += ((-1) ** i) * m[0][i] * determinant(m.slice(1).map(item => item.slice(0, i).concat(item.slice(i + 1))))
        } else {
            det = m[0][0] * m[1][1] - m[0][1] * m[1][0];
            break;
        }
    }

    return det;
};
```

## __Education__ 

- __University:__ Saint Petersburg State University, 
Aerospace Instrumentation (SPb GUAP) (June 2019), 
Informatics and Computer Engineering (09. 03. 01);

- __Courses:__
  - [HTML Academy](https://www.htmlacademy.ru)
  - [FreeCodeCamp](https://www.freecodecamp.org)

## __Languages__

  - __Russian__ - native speaker.
  - __English__ - A2.