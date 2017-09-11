# Hello MVC
### Satish Yadav

---

### What's MVC?

<span class="fragment"> Wait for it... </span>

<span class="fragment"> Model-View-Controller. </span>

+++

Draw the mandatory Model-View-Controller diagram
![MVC Diagram](https://www.pluralsight.com/content/dam/pluralsight/blog/2015/12/tutorial-angularjs-mvc-implementation/wp/img/AngularJS_01.png)

---

### Controller

<span class="fragment"> Orchestrator </span>

<span class="fragment"> Builds Model and selects View </span>


+++

### Model

<span class="fragment"> Data. </span>

<span class="fragment"> From File System/ Database/ Web-Service... </span>

+++

### View

<span class="fragment"> Rendering HTML/UI </span>

<span class="fragment"> Displays Model data </span>

---

### MVC is...

<span class="fragment"> A Design Pattern </span>

<span class="fragment"> Architecure based on SoC and DRY </span>

+++ 

### MVC is not...

<span class="fragment"> A software which you can install </span>

<span class="fragment"> Something Microsoft has invented </span>

+++

<span class="fragment"> Struts (Java) </span>


<span class="fragment"> Ruby on Rails </span>

<span class="fragment"> Django </span>

<span class="fragment"> ... are MVC </span>

---

### ASP.NET MVC over ASP.NET Web-Forms 

+++

### Loosely Coupled
<span class="fragment"> View isn't bound to any ````.aspx.cs```` code-behind. </span>
 
+++

````HTTP```` is stateless for god's sake
<span class="fragment"> No illusion of State or ````Page```` life-cycle </span>

+++

### Clear URLs

<span class="fragment"> http://satishyadav.com/Users/GetUserPhoto.aspx?userPhotoId=123 </span>

<span class="fragment"> vs. </span>

<span class="fragment"> http://satishyadav.com/Users/Photo/123 </span>

+++

### Clean HTML

<span class="fragment"> No ViewState, no wierd client Ids, no gibberish stuff. </span>

+++ 

Alright, so I forget everything I learnt in ASP.NET Web-Forms, then? </span>
 
<span class="fragment">No, it's still ASP.NET under. </span>

+++  

Caching, Cookies, modules, providers, handlers etc. (all the good stuff) are still there.

---

Enough talk! Show me code, already!

---

### Moving parts of ASP.NET MVC

+++

### Routing

<span class="fragment"> How on earth, an HTTP request lands on a ````C#```` class? </span>

+++ 

### Model Binding

<span class="fragment"> So you don't have to ````Request.Get("txtCustomerName")```` </span>

+++

### Data Annotations

<span class="fragment"> Write once, use anywhere... </span>

+++

### Authorization

<span class="fragment"> ````~~if(User.Role == "Admin"){...}~~```` </span>

---

### Visual Studio is your perfect (coding) companion
 
+++
 
### Scaffolding

+++ 

### Surround

+++ 

### Code Snippets

+++ 

### Keyboard Short-cuts

<span class="fragment"> Ctrl+B </span>

<span class="fragment"> Ctrl+F5 </span>

<span class="fragment"> Ctrl+Shift+F5 </span>

<span class="fragment"> F12 </span>

<span class="fragment"> Alt+F12 </span>

<span class="fragment"> F9, F10 and F11 </span>

<span class="fragment"> and more... </span>

---

## Thank you, Happy Coding!