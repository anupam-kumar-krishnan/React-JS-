# _Namaste React EP1 Part 01_ 🚀
- A JavaScript Library, not a Framework

### _Episode 1_

_Before Starting_
1. Make Notes
2. Use Laptop - Learn and Apply the same
3. Maintain a GitHub Repository

### _Tools_
- Google Chrome(Developer Console)
- VS Code

### _Small Recap of HTML, CSS and JS_
- Hello World

### _Homework_
- CDN
- Crossorigin

### _Simple Hello World in HTML5_
<b>


```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Namaste React</title>
  </head>
  <body>
    <div id="root">
    <h1>Hello World!</h1>
    </div>
  </body>
</html>
```
</b>

### _Hello World Using JavaScript_
<b>


```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Namaste React</title>
  </head>
  <body>
    <div id="root"></div>
   <script>
     const heading = document.createElement("h1");
     heading.innerHTML = "Hello World from JavaScript!";
     const root = document.getElementById("root");
     root.appendChild(heading);
   </script>
  </body>
</html>
```
</b>

### _Eject React JS in HTML5_

- First, get React into the project
- Get React by using CDN(Content Delivery Network)
- CDN: These are the website where particular codes are hosted and we are just pulling that code into our project

### _HTML5_

<b>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Namaste React</title>
  </head>
  <body>
    <div id="root"></div>
   <script crossorigin 
    src="https://unpkg.com/react@18/umd/react.development.js">
   </script> // Core of React
   <script crossorigin 
    src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"> 
   </script> //React Library for DOM Operations
  </body>
</html>
```

</b>


### _Use React in HTML5_

## _Why there are two file?_
- First file consists **_Core of React_**
- Second file consists the **_React Library for DOM Operations_** or we can say this is the **_file that we need to modify the DOM_**


### _Can't we have both the files combined at one?_
- Because **_React_** just not work on **_browsers_**, but **_mobiles_** too i.e. **_React-native_**
- **_React DOM_** is like a **_bridge_** between **_React and Browsers_**


### _Whats happens when we eject React JS in HTML?_

- As soon as we eject React JS in HTML, we can actually check in console that we can see React over there and this React JS is available for us to use.
- Now, we can use React into our code.
- This gives a lot of important methods & functions to use.

