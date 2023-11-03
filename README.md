# Web Application: Hierarchical Category Tree
## **Score: 30/30L**

### Team Members:
> - [**Fiore** Jonathan](https://github.com/JonathanFiore)
> - [**Gallicola** Renato](https://github.com/RenatoGallicola)

<br/>

---
<br/>

### Programming Languages:
> - <p>Java (Usage of Java Servlet)<p> 
> - <p>SQL<p>
> - <p>HTML<p>
> - <p>CSS<p>
> - <p>JavaScript<p>

<br/>

---
<br/>

### Tools and Platforms used:
> - <p>IDE: Eclipse<p>
> - <p>SQLWorkbench<p>
> - <p>GitHub<p>

<br/>

---
<br/>

### Description:

<p>The purpose of this application is to manage a Hierarchical Tree of Categories stored in a Database<p>

<p>The user can log into the System with Username and Password and visualize the tree which is in common amoung all the users<p>

<p>The user can create categories and can also copy a subtree to another location of the tree<p>

<p>Each category has a unique ID<p>

**Example:**
<p> Hierarchical Tree: <p>

<pre>
9 Materiali solidi
    91 Materiali inerti
        911 Inerti da edilizia 
            9111 Amianto 
                91111 Amianto in lastre
                91112 Amianto in frammenti
            9112 Materiali cementizi 
        912 Inerti ceramici 
            9121 Piastrelle 
            9122 Sanitari 
    92 Materiali ferrosi 
</pre>

<p> Let's say that we want to copy the subtree which has root ID: 9111 under the category with ID: 9, this will be the result: <p>

<pre>
9 Materiali solidi
    91 Materiali inerti
        911 Inerti da edilizia 
            9111 Amianto 
                91111 Amianto in lastre
                91112 Amianto in frammenti
            9112 Materiali cementizi 
        912 Inerti ceramici 
            9121 Piastrelle 
            9122 Sanitari 
    92 Materiali ferrosi
    93 Amianto 
        931 Amianto in lastre
        932 Amianto in frammenti
</pre>

#### The application has been created in 2 versions:
> - Pure-HTML **--> Static web pages** 
> - RIA (Rich Internet Application) **--> Dynamic Web Pages**

_(To simplify the project a concurrency access to the tree has not been managed)_

<br/>

---
<br/>

### Pictures:

#### Login Page:
<img src="Login.png" alt="Image 1">

#### Home Page:
<img src="HomePage.png" alt="Image 2">


#### Copy Sub Tree:
 The following images show how to copy a subtree with **Drag & Drop function** and give then the possibility to save the chances in the database

<img src="D&D1.jpg" alt="Image 3">
<img src="D&D2.jpg" alt="Image 4">

_Theese pictures are only about the RIA version_
