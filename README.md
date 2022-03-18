# Ihor Nahaev

### Frontend Developer

---

### Contact information:

**Phone:** +375 29 two 48 19 98  
**E-mail:** blgarnag@gmail.com  
**Telegram:** @blgar   
[LinkedIn](https://www.linkedin.com/in/igor-nagaev/)   

---

### Several facts about me:

I've always been keen on computers and information technologies. I decided to combine my job and my hobby in the end of 2020.      
I chose front-end web development. I learned HTML/CSS, JavaScript, then React/Redux, TypeScript. I used the next resources:
* the books for beginners
* learn.javascript.ru
* React/Redux course "ReactJS - way of samurai" by it-incubator.by
* courses from the Udemy platform
* official documentation
* others free courses in network

Sometimes I solve algorithmic problems (for example, [CodeWars](https://www.codewars.com/users/graywa) ).  
From the significant, using React/Redux I developed SPA "Social network for developers".  

---

### Technical skills:

* JavaScript
* TypeScript 
* React 
* Redux / Redux Toolkit
* Redux Form / Formik
* Redux Thunk / Redux Saga
* WebSocket
* HTML/CSS SASS/SCSS
* Styled-Components
* Git/GitHub
* Unit tests

---

### CodeWars:

![CodeWars](https://www.codewars.com/users/graywa/badges/large?theme=light)

----

### Code example:

```
import {useState} from 'react'

export const useFetching = (callback) => {
  const [isLoading, setIsLoading] = useState(false)
  const [error, setError] = useState(null)

  const fetching = async (...args) => {
    try {
      setIsLoading(true)
      await callback(...args)
    } catch(e) {
      setError(e.message)
    } finally {
      setIsLoading(false)
    }
  }

  return [fetching, isLoading, error]
}
```
---

### Education:

* Belarussian state university of informatics and radioelectronics

---

### Courses

- RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)

---

### Languages

* English — A2/B1   
* Belorussian — native  
* Russian — native

---

