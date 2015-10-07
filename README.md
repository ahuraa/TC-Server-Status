# TrinityCore Server Status

This is a simple web application built with [AngularJS](https://angularjs.org/) and [Bootstrap](http://getbootstrap.com) to show the online players list of a TrinityCore server.

It is based on the [TrinityCore JSON RESTful API](https://github.com/ShinDarth/TC-JSON-API/).

![TrinityCore Server Status](https://raw.githubusercontent.com/ShinDarth/TC-Server-Status/master/img/screenshot.png "TrinityCore Server Status")

## Installation

The application requires the [TrinityCore JSON RESTful API](https://github.com/ShinDarth/TC-JSON-API/) to access to the **characters** database.

Clone the TC-Server-Status folder inside your web server directory:

`git clone https://github.com/ShinDarth/TC-Server-Status.git`

Then copy the file **config.js.dist** to **config.js**, open it and set properly with the path of the API:

`app.api = "../TC-JSON-API/public/index.php/";`

and the name of your server:

`app.serverName = "YourServerName";`

### License

The TrinityCore Server Status is open-sourced software licensed under the [GNU GPL license](https://github.com/ShinDarth/TC-Server-Status/blob/master/LICENSE).
