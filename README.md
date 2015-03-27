# Simple Parse Push App

This simple app was built during the March 2, 2015 meeting of [GDG-A3](http://www.meetup.com/gdg-a3).
It enables push messaging via [Parse.com](http://parse.com) and uses a few channels to show how
channels can be used to segment push messages.

In order to make this code work, you will need to setup your own account on [Parse.com](http://parse.com),
create an app and use the application ID and client keys to substitute in the `Parse.initialize()` call
in `GDGTestApplication.java`.