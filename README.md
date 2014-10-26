angular-bootstrap-ratings
=========================

Contains minimal amount of bootstrap modules needed to implement
5 star ratings with basic statistics like below:

![Screenshot](https://github.com/graspeo/angular-bootstrap-ratings/blob/master/screenshot.png)


These are the modules used.
```js
angular.module("ui.bootstrap.ratings", [
"ui.bootstrap.transition",
"ui.bootstrap.collapse",
"ui.bootstrap.progressbar",
"ui.bootstrap.rating",
"template/progressbar/progressbar.html",
"template/rating/rating.html"
]);
```

Installation:
```bash
bower install angular-bootstrap-ratings
```

Usage:
```js
angular.module('myModule', ['ui.bootstrap.ratings']);
```

Based on angular version below

http://angular-ui.github.io/bootstrap/

Version: 0.11.2 - 2014-09-26

License: MIT

