# The Kinvey Bookshelf

The Kinvey Bookshelf demo application, demonstrating how to use the Kinvey JavaScript Library.

## HTML5

The application in the `html5` folder is a simple bookshelf demo for use with HTML5 compliant browsers.

### Kinvey features in this app

* [Caching](http://docs.kinvey.com/js-developers-guide.html#caching)
* Data [persistence](http://docs.kinvey.com/js-developers-guide.html#appdata)
* [Offline](http://docs.kinvey.com/js-developers-guide.html#OfflineStore) usage

### Set up

In `scripts/app.js`, replace `<your-app-key>` and `<your-app-secret>` (lines 13–14) with your application credentials.

## Node.js

The folder `nodejs` contains a simple script for pipelining two requests to the Kinvey service. It can be used to reduce the number of round-trips made by the client. In this example, the script will return the complete Kinvey Bookshelf, together with a number of book genres.

### Set up

To run the server, clone the repository and install the Kinvey npm module:

	`npm install kinvey`

Next, run `node union.js` and make a request to `http://localhost:1234`. Don’t forget to set your application key and secret in `union.js`.

### Acknowledgements
This project uses the following third party projects:

* [Twitter Bootstrap](https://github.com/twitter/bootstrap) (Apache License 2.0)
* [jQuery](https://github.com/jquery/jquery) (MIT License)

### More
Please visit [kinvey.com](http://www.kinvey.com) for more information about our services.