### Hello MVC
##### Satish Yadav

---

What's MVC?

---
Surprise...
Model-View-Controller

---

Draw the mandatory Model-View-Controller diagram
![MVC Diagram](https://www.pluralsight.com/content/dam/pluralsight/blog/2015/12/tutorial-angularjs-mvc-implementation/wp/img/AngularJS_01.png)

---

**Controller**

Orchestrator.

Builds Model and selects View

---

**Model**

Data.

From File System/ Database/ Web-Service... 

---

**View**

Rendering HTML/UI

Displays Model data

---


MVC is...

--- 

MVC is not...

--- 

Definitely not something Microsoft has invented.

---

Struts (Java)
Ruby on Rails
Django
... are MVC

---

Web Forms vs MVC

Loosely Coupled

Not bound to any aspx page.
 
---

````HTTP```` is stateless for god's sake

No illusion of State or ````Page```` life-cycle

---

Clear URLs
http://satishyadav.com/Users/GetPhoto.aspx?photoId=123
	vs
http://satishyadav.com/Users/Photo/123

---

Clean HTML

No ViewState, no wierd client Ids, no gibberish stuff.

---

So, it must be something very different than?

---

No, it's still ASP.NET

Caching, modules, providers, handlers etc. (all the good stuff) are still there.

---

**Enough talk! Show me code, already!**

---

**Moving parts of ASP.NET MVC**

---

**Routing**

How on earth, an HTTP request lands on a ````C#```` class?

---

**Model Binding**

So you don't have to ````Request.Get("txtCustomerName")````

---

**Data Annotations**

Write once, use anywhere...

---

**Authorization**

~~if(User.Role == "Admin"){...}~~

---

Visual Studio is your perfect (coding) companion

---
