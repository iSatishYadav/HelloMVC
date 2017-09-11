# Hello MVC
### Satish Yadav

---

### What's MVC?

+++

<span>Wait for it... </span>

<span> Model-View-Controller </span>

+++

Draw the mandatory Model-View-Controller diagram
![MVC Diagram](https://www.pluralsight.com/content/dam/pluralsight/blog/2015/12/tutorial-angularjs-mvc-implementation/wp/img/AngularJS_01.png)

---

 ### Controller

+++

Orchestrator. |

Builds Model and selects View |


+++

 ### Model

Data. |
From File System/ Database/ Web-Service... |

+++

### View

Rendering HTML/UI |
Displays Model data |

---

### MVC is...

A Design Pattern |
Architecure based on SoC and DRY |

+++ 

 ### MVC is not...

A software which you can install |
Something Microsoft has invented |

+++

Struts (Java) |
Ruby on Rails |
Django |
... are MVC |

---

 ### ASP.NET MVC over ASP.NET Web-Forms 

+++

 ### Loosely Coupled
View isn't bound to any ````.aspx.cs```` code-behind. |
 
+++

-  ````HTTP```` is stateless for god's sake
 No illusion of State or ````Page```` life-cycle

+++

 ### Clear URLs

http://satishyadav.com/Users/GetUserPhoto.aspx?userPhotoId=123 |

vs.

- http://satishyadav.com/Users/Photo/123 |

+++

 ### Clean HTML

No ViewState, no wierd client Ids, no gibberish stuff. |

+++ 

Alright, so I forget everything I learnt in ASP.NET Web-Forms, then? |
 
No, it's still ASP.NET under. |

+++  

 Caching, Cookies, modules, providers, handlers etc. (all the good stuff) are still there.

---

 Enough talk! Show me code, already!

---

 ### Moving parts of ASP.NET MVC

+++

 ### Routing

How on earth, an HTTP request lands on a ````C#```` class? |

+++ 

 ### Model Binding

So you don't have to ````Request.Get("txtCustomerName")```` |

+++

 ### Data Annotations

Write once, use anywhere... |

+++

 ### Authorization

~~if(User.Role == "Admin"){...}~~ |

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

Ctrl+B |
Ctrl+F5 |
Ctrl+Shift+F5 |
F12 |
Alt+F12 |
F9, F10 and F11 |
and more... |

---

## Thank you, Happy Coding!