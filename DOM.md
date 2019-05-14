# DOM: Document Object Model

### 1. Why DOM?
>It is an interface that allows programs and scripts to dynamically access and update the content, structure, and style of a document.

### 2. Objective
+ How to
    + change the content of HTML elements
    + change the style (CSS) of HTML elements
    + react to HTML DOM events
    + add and delete HTML elements

### 3. JavaScript - HTML DOM Methods
+ What is **property** and what is **method**

+ Illustrate different ways to select HTML elements. For example:- 
**getElementById**


```javascript
<html>
<body>

<p id="demo"></p>

<script>
    document.getElementById("demo").innerHTML = "Hello World!";
</script>

</body>
</html>
```


### 5. What are different ___methods___ and ___property___ available in DOM?

+ Illustrate Methods:-
    + getElementById
    + getElementsByTagName
    + getElementsByClassName

+ Illustrate Property:-
    + innerHTML
    + attribute
    + style.property

+ Adding and Deleting elements

### 6. How to add event handling?

+ Why event handling?

+ Illustrate with examples

```javascript
document.getElementById(id).onclick = function(){code}
```

OR

```javascript
<!DOCTYPE html>
<html>
<body>

<h1 onclick="changeText(this)">Click on this text!</h1>

<script>
function changeText(id) { 
  id.innerHTML = "Ooops!";
}
</script>

</body>
</html>
```

### 7. Finding different HTML Objects

+ Illustrate some ways to get the HTML element in JavaScript

+ Example

```javascript
document.anchors //Returns all <a> elements that have a name attribute

document.images //Returns all <img> elements

//... ext

```