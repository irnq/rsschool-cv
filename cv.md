# Rybakov Ilia

## Contacts:

- **Tel:** +7-963-545-87-58
- **Telegram:** @ironiqpie
- **E-mail:** Sk1m1gm@gmail.com

## Summary

I work as a design engineer for a laser cutting manufacturing company. I write programs for CNC machines and wrote several scripts for autocad on autolisp. But I want to become a real programmer and so I decided to move on and my choice fell on **Web development** and **Front-end** in particular. I came to **"The Rolling Scopes School"** to improve my skills and do interesting projects.

## Skills

- _HTML/CSS/JavaScript_
- _Git_
- _Figma/Photoshop_

## Code example

My favorite method is **reduce()** , so I gave an example from CodeWars's kata **Array Deep Count**

> Array.prototype.length will give you the number of top-level elements in an array. Your task is to create a function deepCount that returns the number of ALL elements within an array, including any within inner-level arrays. The input will always be an array.

**My code:**

```
function deepCount(a){
  return a.reduce((lenght, el) => lenght+= Array.isArray(el) ? deepCount(el) + 1 :  1 , 0)
}
```

## Education

- Izhevsk State Technical University

## Language

- Russian
- English(A2)
