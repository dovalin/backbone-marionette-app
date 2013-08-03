Testing backbone-marionette apps using Yeoman (http://yeoman.io/) using yeoman marionette generator (https://github.com/mrichard/generator-marionette)

Yeoman generator for Express, Marionette and Backbone with AMD

Stack
-------
- Server: 
    * Node: http://nodejs.org/
    * Express: http://expressjs.com/
    * Socket IO: http://socket.io/
- DB: Mongo: http://www.mongodb.org/
- ODM: Mongoose: http://mongoosejs.com
- Client: 
    * Backbone: http://backbonejs.org/
    * Marionette: https://github.com/marionettejs/backbone.marionette
    * jQuery: http://jquery.com/
    * Require: http://requirejs.org/
    * Handlebars: 
        - http://handlebarsjs.com/
        - https://github.com/SlexAxton/require-handlebars-plugin
        - https://github.com/asciidisco/Backbone.Marionette.Handlebars
    * SASS-Bootstrap:
        - http://twitter.github.io/bootstrap
        - https://github.com/thomas-mcdonald/bootstrap-sass
- Tooling: 
    * Yeoman: http://yeoman.io/
    * Bower:
    * Grunt
- Testing:
    * phantomJS http://phantomjs.org/
    * Mocha http://visionmedia.github.io/mocha/
    * Chai http://chaijs.com/
    * Sinon http://sinonjs.org/


Directory structure
-------
- app/                                --> client side files
    * /bower_components               --> bower installs
    * /images
    * /scripts
        - /vendor                     --> 3rd party scripts
        - /models
        - /collections
        - /controllers
        - /routers
        - /regions
        - /views
            * /item
            * /collection
            * /composite
            * /layout
        - init.js                     --> require configuration
        - main.js                     --> application starting point
        - application.js              --> application file

    * /styles                         --> scss files
    * /templates                      --> handlebar templates

- server/                             --> node server files
- test/                               --> unittesting
    * /spec                           --> individual spec files
