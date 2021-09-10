# Rybakov Ilia
  ## Contacts:
  * **Tel:** +7-963-545-87-58
  * **Telegram:** @ironiqpie
  * **E-mail:** Sk1m1gm@gmail.com
  
  ## Summary

  ## Skills
  * *HTML/CSS/JavaScript*
  * *Git*
  * *Figma/Photoshop*

  ## Code example
  My favorite method is **reduce()** , so I gave an example from CodeWars's kata **Array Deep Count**
>Array.prototype.length will give you the number of top-level elements in an array.
Your task is to create a function deepCount that returns the number of ALL elements within an array, including any within inner-level arrays. The input will always be an array.

**My code:**
````
function deepCount(a){
  return a.reduce((lenght, el) => lenght+= Array.isArray(el) ? deepCount(el) + 1 :  1 , 0)
}
````

  ## Education
  * Izhevsk State Technical University

  ## Language
  * Russian
  * English(A2)