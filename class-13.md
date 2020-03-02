# read 13
## Cookies:
Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
Cookies are limited to about 4 KB of data — enough to slow down your application, but not enough to be terribly useful
# we want:
a lot of storage space
on the client
that persists beyond a page refresh
and isn’t transmitted to the server
## userData:
allows web pages to store up to 64 KB of data per domain
## Flash cookies:
it allows Flash objects to store up to 100 KB of data per domain
## Gears:
an open source browser plugin aimed at providing additional capabilities in browsers
## HTML5 Storage:
it’s a way for web pages to store named key/value pairs locally, within the client web browser, Like cookies.
**The storage event is supported everywhere the localStorage object is supported**
## STORAGEEVENT OBJEC:
key: string: the named key that was added, removed, or modified
oldValue: the previous value (now overwritten), or null if a new item was added
newValue: the new value, or null if an item was removed
url: string	the page which called a method that triggered this change
5 megabytes: is how much storage space each origin gets by default. This is consistent across browsers.
