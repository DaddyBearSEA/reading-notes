# Storage

- If your native client application needs local storage beyond key/value pairs , you can embed your own database, invent your own file format or any other solutions. REMEMBER Access DB's!  

**Cookies**
1. slow down by reading them at every request - transmitting
1. slow down by sending unencrypted data
1. limitation is 4KB of data.

**What we rally realy want!**
1. Lots of storage space
1. On the client side
1. perists beyond a page refresh
1. isn't transmitted to the server


*userData allows web pages to store up to 64KB of data per domain, in a hierarchical SML-based structure*

[HTML5 Storage]<img src = "images/html5Storage.PNG">

`function supports_html5_storage() {`

  `try {`

  ` return 'localStorage' in window &`
  
  `& window['localStorage'] !== `
  
  ``null;``
 ` } catch (e) {`

`    return false;`

 `   }`

`}`


[more code](http://diveinto.html5doctor.com/storage.html) can be found on Dive Into.



*Data is stored as strings. If you are storing something other than a string, you’ll need to coerce it yourself when you retrieve it.*

<img src="images/webSQLDB.JPG">



**The Indexed Database API**
> another competing vision for advanced, persistent, local storage for web applications

[go back](../README.md)