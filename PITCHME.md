# Hello MVC
### Satish Yadav

---

### What's MVC?

<span class="fragment"> Wait for it... </span>

<span class="fragment"> Model-View-Controller. </span>

Note:
Yeah, surprise.

+++

Draw the mandatory Model-View-Controller diagram
![MVC Diagram](https://www.pluralsight.com/content/dam/pluralsight/blog/2015/12/tutorial-angularjs-mvc-implementation/wp/img/AngularJS_01.png)

Note:
Annoying diagram.

---


### Model

<span class="fragment"> Data. </span>

<span class="fragment"> From File System/ Database/ Web-Service... </span>

Note:
Business Logic.

+++

### View

<span class="fragment"> Rendering HTML/UI </span>

<span class="fragment"> Displays Model data </span>

Note:
Fits Model data to appropriate place and style.

+++

### Controller

<span class="fragment"> Orchestrator </span>

<span class="fragment"> Builds Model and selects View </span>

Note:
Requests lands here, we'll see how...

---

### MVC is...

<span class="fragment"> A Design Pattern </span>

<span class="fragment"> Architecure based on SoC and DRY </span>

Note:
Separation of Concerns: Model, View and Controller.
Plug and play.
Do-not Repeat Yourself: Model Validations 

+++ 

### MVC is not...

<span class="fragment"> A software which you can install </span>

<span class="fragment"> Something Microsoft has invented </span>

+++

Struts (Java)

<span class="fragment"> Ruby on Rails </span>

<span class="fragment"> Django </span>

<span class="fragment"> ... are MVC </span>

---

### ASP.NET MVC over ASP.NET Web-Forms 

+++

### Loosely Coupled
<span class="fragment"> View isn't bound to any
<span style="color: #e49436">````.aspx.cs````</span> code-behind. </span>

+++

<span style="color: #e49436">````HTTP````</span></span> is stateless for god's sake

<span class="fragment"> No illusion of State or  <span style="color: #e49436">````Page````</span> life-cycle </span>

<span class="fragment"> No abstraction from <span style="color: #e49436">````HTML/JS/CSS````</span> life-cycle </span>

<span class="fragment"> Easy to Unit Test</span>

Note:

No ViewState.

In MVC Everything is an HTTP Call.

+++

### Clear URLs

<span class="fragment"> http://satishyadav.com/Users/GetUserPhoto.aspx?userPhotoId=123 </span>

<span class="fragment"> vs. </span>

<span class="fragment"> http://satishyadav.com/Users/Photo/123 </span>

+++

### Clean HTML

<span class="fragment"> No ViewState, no wierd client Ids, no gibberish stuff. </span>

Note:

W/F generates a lot of HTML/JS to make Server Side Control to work.

In MVC, you have all the control over what is being generated.

Search Engine Optimization (SEO) Friendly.

+++ 

Alright, so I forget everything I learnt in ASP.NET Web-Forms, then? </span>
 
<span class="fragment">No, it's still ASP.NET under. </span>

+++  

Caching, Cookies, modules, providers, handlers etc. (all the good stuff) are still there.

---

### Enough talk! Show me code, already!

Note:
Create an MVC with No Auth.
Show folder structure.
Show About, Contact and Responsiveness (Bootstrap)

+++

### Add a Model

Note:
Id, Name, Email, Age

+++

### Add a Controller

Note:
Use Scaffolding.
Build and Run.
Show how it's created an full blown CRUD site for Customer Model without writing any code.

---

### Peek inside generated Code

+++

### Controller

<span class="fragment">List</span>

<span class="fragment">Create</span>

<span class="fragment">Edit</span>

<span class="fragment">Delete</span>

<span class="fragment">Confirm Delete</span>

+++

### Entity Framework

<span class="fragment">ORM</span>

<span class="fragment">Handles all the dirty work, like:</span>

<span class="fragment">Connection</span>

<span class="fragment">De-serialization</span>

<span class="fragment">Transactions</span>

<span class="fragment">Disposing a Connection</span>


Note:
Object-relational mapping

+++

### Where is my Database?

<span class="fragment"><span style="color: #e49436">````(localdb\MSQSQLLOCALDB))````</span></span>


---

### Data Annotations

<span class="fragment">Decorate your data with <span style="color: #e49436">````Attributes````</span></span>



### Moving parts of ASP.NET MVC

+++

### Routing

<span class="fragment"> How on earth, an HTTP request lands on a <span style="color: #e49436">````C#````</span> class? </span>

Note:
Show RouteConfig and a sample request.
Map a new Route with default action as About.

+++ 

### Razor

<span class="fragment">
<span style="color:#e49436">````@Html.TextboxFor````</span></span>

+++

### Data Validation (using Annotations)

<span class="fragment"> Write once, use anywhere... </span>

<span class="fragment"> <span style="color: #e49436">````ModelState.IsValid````</span></span>


Note:
Create a new Model Customer, add a new Empty Controller.
Don't use initialization syntax, show it afterwards.

Create a 

DRY here.
Data Annotations, MinLength, Data Type

+++

### Model Binding

<span class="fragment"> So you don't have to <span style="color: #e49436">````Request.Get("txtCustomerName")````</span> </span>

Note:
How text-boxes and inputs are bound into Action Method parameters.

+++

### Authorization

<span class="fragment"> <span style="color: #e49436"> ~~````if(User.Role == "Admin"){...}````~~</span> </span>

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

## Thank you!

## Happy Coding!