# LOCAL STORAGE #
###### ()[http://diveinto.html5doctor.com/storage.html] ######

Cookies were invented early on and can be used for local storage on a small scale (about 4b of data). There are downsides to cookies such as slowing down your web application due to it transmitting the same unencrypted data over and over again. 

Before HTML5, Microsoft invented something called "userData" which allowed web pages to store up to a strict max of 64kb of data per domain. Intranets would get about 10 times more. 

In 2002 Adobe introduced Flash 6, properly known as Local Shared Objects that allows flash objects to store up to 100 kb of data per domain for free. in 2007 Google launched Gears, an open source browser plug in aimed to provide additional capabilities in browsers. With permission from user, Gears can store unlimited amounts of data. 

The issue to solve is to provide a standard API that doesn't have to rely on third-party plugins to implement natively and consistently in multiple browsers. HTML5 storage is a way for web pages to store key/value pairs locally within the client browser.