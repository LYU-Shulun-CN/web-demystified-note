# Web Demystified (简明的解释) 教程的笔记  
> Youtube Mozilla Hacks Channel    
> By Jeremie Patonnier  

## What is "The Web" and how does it work? | Web Demystified, Episode 0 | The Web
> Jeremie Patonnier offers an overview of **what the web is and how it works**. If you're just getting started on the web, this is an important overview for you!  

1.The web is a collection of documents that will be requested by a browser from a server.  
> **1.Documents are available on servers.**  

2.Each document is accessible through a web address.  
> **2.Documents are accessible through a web address.**  

3.The browser will mix all the necessary documents to turn any HTML document into a nice web page.  
> **3.Browsers mix documents to render web pages.**  

![What the web is and how it works.](images/what-the-web-is-and-how-it-works.png)  

```c
/* 是重要注意的是：1.SVG 会随着浏览器的不同而渲染出不同的效果；2.文件名不能留空格。 */
```

## What's HTML and how does it work? | Web Demystified, Episode 1  

> Basically HTML is a **descriptive language** that allows us to tell a web browser how to handle text content.  

* By Tim Berners Lee  
* HTML (HyperText Markup Language)
  * a HTML document can create a link to other HTML document  
  * a system to annotate some plain text with tags

1.**HTML is markup langugage**.  
> HTML is a markup language that allows to structure a text in order to make it understandable by web browsers.   

2.**HTML is made of elements formed by tags**.  
> That HTML markup is made of elements formed by tags put around text.  

3.**HTML is maintained by the W3C**.  
All vaild HTML elements and their nesting rules are defined in a specification maintained by the W3C.  

```html
<!DOCTYPE html>
<head>
  <title>...</title>    
</head>
<body>
  <p>My cat is <strong>VERY</strong> grumpy!</p>
</body>
</html>
```

## What is CSS and how does it style web pages? | Web Demystified, Episode 2  
> Like HTML, CSS is a descriptive language, but instead of defining a semantic for some text it defines the look and feel of each HTML element.  

> In other words, CSS is like makeup for HTML.  

* CSS is an acronym standing for Cascading Style Sheets.  
* At the end of the 90's with the idea to create a clear distinction between text semantics and presentation.
 * 1996, CSS1
 * 2011, CSS2  
 * CSS3 -> More fine grain, Since than  

 There are 3 ways to apply CSS to an HTML document. But the below way is the only way recommanded.  

 ```html
 <link rel="stylesheet" href="styles.css">
 ```  

 CSS rule:  
 ```css
 selectors {
    property name: property value;
 }
 ```


## What is JavaScript and how does it work? | Web Demystified, Episode 3  
> JavaScript is the programing language at the heart of the modern web.  

* crated in 1995, but very quickly in 1997, it has been standardized at the standards organization ECMA International under the name ECMAScript.  
* ECMAScript defines the basic syntax of the language, and its core mechanisms. But in itself, it doesn't do very much.  

* Two flavors of JavaScript:  
    * JavaScript in the browser:  
        * modify your HTML doc (DOM)  
        * making network requests (Fetch XMLHttpRequest)  
        * managing data (Web Storage IndexedDB)  
        * doing audio and graphics redering (Web Audio / WebGL / Canvas 2D)  

    * JavaScript on the server (node.js)  
        * manage the computer directly  
        * accesss files and folder  
        * handle network resources  
        * spawn processes  
        * etc.


## What are Scalable Vector Graphics (SVG) & how are they special? | Web Demystified, Episode 4  | SVG
> to do...


## How do web browsers work? | Web Demystified, Episode 5  | How browsers work?
> to do...
