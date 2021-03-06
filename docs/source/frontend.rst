Frontend
========

The frontend, written in JavaScript, requires modern (HTML5 enabled) web browsers.
It is an `angularjs`_ app, which was scaffolded using `yeoman`_, and `angular`_ generator.
It uses the `D3.js`_ library to render images and the force directed graphs.

Dependencies
------------

The project requires the `node`_ (https://nodejs.org/en/) runtime to build the app,
`Grunt`_ (http://gruntjs.com/) to run tasks,
and the package managers `npm`_ (https://www.npmjs.com/) and `bower`_ (http://bower.io/)
to install development and production dependencies respectively.

Building
--------

To build and serve the project (having installed `node`_ and `npm`_), you can change to the frontend directory and run:

.. code-block:: bash

  $ npm install -g grunt bower      // install grunt and bower
  $ npm install                     // install node modules
  $ bower install                   // install bower modules
  $ grunt build                     // build the server
  $ python -m SimpleHTTPServer 8000 // run the server

Your default browser should open by default to ``localhost:8000``, where the app is being
served.

.. _angularjs: http://angularjs.org
.. _yeoman: http://yeoman.io
.. _angular: https://github.com/yeoman/generator-angular
.. _D3.js: https://d3js.org
.. _node: https://nodejs.org
.. _bower: https://bower.io
.. _npm: http://npmjs.com
.. _grunt: http://gruntjs.com
