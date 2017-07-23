# green-gate

Project **green-gate** is a static site build by the Brothers of the Mu Chapter of the Chi Phi Fraternity.

### Tech

green-gate uses a number of open source projects to work properly:

* [Twitter Bootstrap] - UI boilerplate
* [node.js] - duh
* [Gulp] -  build system

### Development

Developing green-gate requires [Node.js](https://nodejs.org/), as well as NPM (typically installed with Node).

First, clone this repository (if you haven't already):
```sh
$ git clone https://github.com/green-gate/green-gate.github.io.git
```

Once Node & NPM are installed, and you have the repo cloned locally, it's time to install the dependencies.

The following will enter the site directory, install Gulp globally using npm (may need sudo/root for this), then install the remaining project dependencies.

```sh
$ cd green-gate.github.io
$ sudo npm install -g gulp
$ npm install
```

Lastly, run gulp serve and keep the terminal open to watch the project files for changes and re-compile when necessary.

```sh
$ gulp serve
```

Changes can be seen locally by opening the files in your browser.

### Contributing
If contributing upstream, remember to **never** push to master. Always work on a dev/feature branch, push the new branch to remote, and merge to master via pull request in GitHub.
When in doubt, refer to [GitFlow](https://www.atlassian.com/git/tutorials/comparing-workflows) workflow.

### Todos

 - Index/Home Page markdown & styling
 - Global navbar styled
 - Responsive Roster page
 - House/History page
 - Probably more..


[//]: # (These are reference links used in the body)

   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [Gulp]: <http://gulpjs.com>
