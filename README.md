# weatherpackAPI

weatherpackAPI is an application that helps display weather of any place in the world.

# Contributors

Owen. 2017

# Technologies

The application uses:
* HTML
* javascript
* sass
* node [npm]
* webpack - this a building tool for the application
* babel - this transpiles ES6 to ES5

# Instructions

The following will help in setting up the application to run.

You will be using **node** to install all **npm** packages, so install node first. Check out how to install node from its website. Visit *http://nodejs.org*.

To use webpack development dependency you need to install **webpack** globally in your machine. Run this at the root of your home.

```shell
$ npm install webpack -g

# if that does not help install as an administrator
$ sudo npm install webpack -g
```

* We should install all the dependencies the application uses.

```shell
$ npm install
```
* Visit *http://openweathermap.org* to get your API key and save it in the _.env_ file at the root of the directory.

_.env_
```env
module.exports = "xxxxxxxxxxxxxxxxxxxxxxxxx";
```
* To run your application you need to bundle all the _sass_, _js_ files, that's where `webpack` comes in. `cd` into the root of the project directory and type.

```shell
$ webpack
```
* Run the application by opening the _index.html_ file in your default browser.

## HAPPY CODING :)
