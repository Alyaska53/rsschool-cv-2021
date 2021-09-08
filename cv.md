# Dmitry Buravkin

### Contact information:

**Phone:** +375 (29) 8930685  
**Email:** dmitry.buravkin@gmail.com  
**Telegram:** @DmitryBuravkin  
[LinkedIn](https://www.linkedin.com/in/dmitry-buravkin-6168b9219/)  

***

### Briefly about myself: 

In 2020 I graduated from the _Belarusian National Technical University_ with a degree in _Power Engineering_.  
Today I work as an electrical design engineer.  

Recently I realized that the chosen profession is not suitable for me. So I decided to try my hand at web development.  
I enjoy learning and solving various problems in this direction.  

I really want to become a good _front-end developer_ and I'm going to my goal!

***

### Skills and Proficiency:

* HTML5, CSS3  
* JavaScript Basics  
* Git, GitHub  
* VS Code
* Figma  
* Autodesk AutoCAD
* Autodesk Revit

***

### Code example:

**KATA from CODEWARS**: _Write a function that takes a string of parentheses, and determines if the order of the parentheses is valid._  
_The function should return_ `true` _if the string is valid, and_ `false` _if it's invalid._

```
function validParentheses(parens) {
  if (parens.length > 100) {
    return false;
  }
      
  const brackets = parens.split('')
                         .filter(el => (el === ')') || (el === '('));  
  const stack = [];
  
  brackets.forEach(function(element) {
    if (element === '(') || 
        stack.length === 0 ||
        stack[stack.length - 1] === ')') {
      
      stack.push(element);
      return;
    } 
    
    stack.pop();
    return;
  });
  
  return stack.length === 0;
}
```
***

### Courses:

* HTML and CCS Tutorials on the [Code-Basics](https://ru.code-basics.com/) (completed)
* JavaScript Manual on [learn.javascript.ru](https://learn.javascript.ru/) (in progress)
* RS School Course "JS / FRONT-END" (in progress)
* Training on algorithms from Yandex (in progress)

***

### Languages:

* Russian (native)
* Belarusian (native)
* English (А2)