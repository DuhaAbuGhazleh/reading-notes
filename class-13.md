# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

**ersistent local storage:**

 is one of the areas where native client applications have held an advantage over web applications. 

Negatives of Cookies:

- Cookies are included with every HTTP request, thereby slowing down your web application

- Cookies are included with every HTTP request, thereby sending data unencrypted over the internet

- Cookies are limited to about 4 KB of data — enough to slow down your application but not enough to be useful

## HTML5 STORAGE

**“HTML5 Storage” is a specification named Web Storage**

**what is HTML5 Storage?**

it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. 

**Which browsers?**

the latest version of pretty much every browser supports HTML5 Storage

- IE 8.0+	/FIREFOX 3.5+	/SAFARI 4.0+/	CHROME 4.0+/	OPERA 10.5+/	IPHONE 2.0+	/ANDROID 2.0+

**How to check for HTML5 Storage?**

you can use **Modernizr** to detect support for HTML5 Storage

**HOW TO USE HTML5 STORAGE?**

is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key.

- named key is a string. 

- The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats


* Calling setItem() with a named key that already exists will silently overwrite the previous value. 

* Calling getItem() with a non-existent key will return null rather than throw an exception.

- you can treat the localStorage object as an associative array. Instead of using the getItem() and setItem() methods

- methods for removing the value for a given named key, and clearing the entire storage area

`interface Storage {`

  `deleter void removeItem(in DOMString key);`

  `void clear();`

`};`

*Calling removeItem() with a non-existent key will do nothing.*

-  property to get the total number of values in the storage area, and to iterate through all of the keys by index 

`interface Storage {`

  `readonly attribute unsigned long length;`

  `getter DOMString key(in unsigned long index);`

`};`

 *call key() with an index that is not between 0–(length-1), the function will return null.*
 

 **TRACKING CHANGES TO THE HTML5 STORAGE AREA**

  The storage event is fired on the window object whenever *setItem()*, *removeItem()*, or *clear()* is called and actually *changes something*


  **LIMITATIONS IN CURRENT BROWSERS**

  - “5 megabytes” is how much storage space each origin gets by default

  -  keep in mind is that you’re storing strings, not data in its original format.

  - “QUOTA_EXCEEDED_ERR” is the exception that will get thrown if you exceed your storage quota of 5 megabytes.

  **HTML5 STORAGE IN ACTION**

   it restores  values BY using the localStorage object.

