![cf](http://i.imgur.com/7v5ASc8.png) lab-35 socrata router
====

[![Issues?](https://img.shields.io/badge/Issues%3F-Ask%20for%20Help!-55cbe0.svg)](https://github.com/codefellows/seattle-javascript-401n1/issues/new)

# To Submit this Assignment
  * fork this repository
  * write all of your code in a directory named `lab-` + `<your name>` **e.g.** `lab-duncan`
  * push to your repository
  * submit a pull request to this repository
  * submit a link to your PR in canvas
  * write a question and observation on canvas

# Directions
* Create these directories to organize your code: 
 * app
 * app/component
 * app/service
 * app/html
 * app/scss/vendor
* create a **_theme.scss** partial 
 * add three color variables
* create a **base.scss** file 
 * import normalize
 * import bootstrap
 * import \_theme
 * write some styles that use the color variables defined in \_theme
* create a **entry.js**
 * require your **index.html** and force webpack to use the `file-loader`
 * require your **base.scss**

# Requirements
* Create a new app using data from the socrata apis
 * Search for interesting data on [opendatanetwork.com](http://opendatanetwork.com)
 * For help read the api docs at [dev.socrata.com](http://dev.socrata.com)
* Create an app with a router with 3 routes
 * `/#/about` -> that should contain a landing page describing your site
 * `/#/data` -> that should have a list of populated data from a socrata API endpoint
 * `otherwise` -> a 404 page with a like back to `/#/about`
* Build this app using only the `.component` syntax, aka. no `.directive`'s
* Your app should not have a main directive
* signup with open data network and register an app to get an app token before you get started!!
* remember to send your app toekn in the query string [APP TOKEN](https://dev.socrata.com/docs/app-tokens.html)

# Test
 * write test for any service methods and controller methods

# Bonus 
* *2pts* create a hamburger menu for page navigation
