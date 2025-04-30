#Simple Node.js Static File Server
This is a simple Node.js project that serves different HTML pages based on the URL path. The server responds with the appropriate HTML page for specific routes like /, /about, and /contact-me. Any other URL will result in a 404 page.

##Features
Serves static HTML pages:

Home Page at /

About Page at /about

Contact Me Page at /contact-me

404 Page for unknown URLs



I have used  http module to handle requests and serve the correct HTML files

The server will start running at http://localhost:8080.

####Testing the Routes
Visit http://localhost:8080 for the Home Page.

Visit http://localhost:8080/about for the About Page.

Visit http://localhost:8080/contact-me for the Contact Me Page.

Any other URL (like /some-page) will show the 404 Page.