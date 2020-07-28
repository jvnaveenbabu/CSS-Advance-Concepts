# CSS-Advance-Concepts
This repository consist of some advance concepts of CSS

## 1. CSS Variable
* The var() Function

Variables in CSS should be declared within a CSS selector that defines its scope. For a global scope you can use either the :root or the body selector.

The variable name must begin with two dashes (--) and is case sensitive!

The syntax of the var() function is as follows:

```
var(custom-name)
```

## 2. CSS ::selection Selector
* The selection selector matches the portion of an element that is selected by a user 
*  Only a few CSS properties can be applied to the ::selection selector like color,
   background, cursor and outline
* **Browser by default property** while highlighting the text is **background** is **blue** and **color** is **white**

## 3. Three Ways to Center a Div inside another Div

* Method 1 :
```
position: relative;
left: 50%;
top: 50%;
transform: translate(-50%, -50%);
```
* Method 2 : 
```
display: flex;
justify-content: center; /*Centering horizontally*/
align-items: center;  /*Centering Vertically*/
           
```
* Method 3 :
```
display: grid;
place-items: center;
```
