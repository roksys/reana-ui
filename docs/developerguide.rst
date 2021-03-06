.. _developerguide:

Developer guide
===============

Quick start
-----------

This guide explains how to locally-start REANA-UI, with reloading activated:

1. Clone reana-ui Github project into your computer

   .. code-block:: console

      $ git clone https://github.com/reanahub/reana-ui.git

2. Install all the project dependencies:

   .. code-block:: console

      $ cd reana-ui/reana-ui
      $ npm install

3. Launch the web server

   .. code-block:: console

      $ npm start
      ...
      Compiled successfully!

      You can now view reana-ui in the browser.

        http://localhost:3000/

      Note that the development build is not optimized.
      To create a production build, use npm run build.

4. Open the browser in localhost:3000 (address by default)


Code style
----------

We are using Prettier to format our code. In order to use it before a Pull Request:

1. Install the package from NPM

   .. code-block:: console

      $ npm install prettier


2. Style your code

   .. code-block:: console

      $ prettier --write **/*.js
