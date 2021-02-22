# Read 13

### THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

ersistent local storage is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files, or some other place according to platform convention. If your native client application needs local storage beyond key/value pairs, you can embed your own database invent your own file format, or any number of other solutions.
* Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
* Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
* Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful.
**What we really want is**
* a lot of storage space
* on the client
* that persists beyond a page refresh
* and isn’t transmitted to the server
* What I will refer to as “HTML5 Storage” is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons.
![HTMLStorage](../imges/HTMLStorage.PNG);


If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.

**BEYOND NAMED KEY-VALUE PAIRS: COMPETING VISIONS**
![SQL_database](../imges/SQL_database.PNG);

