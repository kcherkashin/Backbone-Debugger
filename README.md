Backbone Debugger
=================

Chrome extension for real-time debugging of JavaScript Applications made with the Backbone framework.

Features
--------
* Adds a panel under the Chrome Developer Tools that displays in real-time all your application views, models, collections and routers. Data displayed includes:
    * Views: rendering status, html element, associated model and/or collection, **handled page events**, events triggered
    * Models: sync status, **attributes**, id, cid, url, associated collection, events triggered, **sync actions**
    * Collections: sync status, **models**, url, events triggered, **sync actions**
    * Routers: events triggered (include **routes**)
* Extends the sidebar of the developer tools "Elements" panel to display the Backbone View of the inspected html element.

Install from source
--------
* Open Chrome.
* [Download the project tarball](https://github.com/Maluen/Backbone-Debugger/archive/master.zip).
* Click on Tools -> Settings -> Extensions
* Select the "Enable developer mode" checkbox in the upper right of the window.
* Click on "Load unpacked extension"
* Select the downloaded src folder.
* Enjoy!

Screenshots
--------
**Views**:

![Views](http://img827.imageshack.us/img827/7707/viewsf.jpg "Views")

**Models**:

![Models](http://img442.imageshack.us/img442/9179/models.jpg "Models")

**Collections**:

![Collections](http://img4.imageshack.us/img4/8056/collectionsq.jpg "Collections")

**Routers**:

![Routers](http://img23.imageshack.us/img23/7677/routerse.jpg "Routers")

**Elements sidebar extension**:

![Elements sidebar extension](http://img842.imageshack.us/img842/1971/elementssidebar.jpg "Elements sidebar extension")
