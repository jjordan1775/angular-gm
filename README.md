# AngularGM

AngularGM is a set of directives for embedding Google Maps in your application using the Google Maps Javascript API.


## Quick Start

Include the required libraries

```html
<script src="//maps.googleapis.com/maps/api/js?sensor=false"></script>
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
<script src="//ajax.googleapis.com/ajax/libs/angularjs/1.0.5/angular.min.js"></script>
<script src="//dylanfprice.github.com/angular-gm/dist/angular-gm-0.0.1.min.js"></script>
```

Declare a dependency on the `AngularGM` module

``` javascript
var app = angular.module('myModule', ['AngularGM']);
```


## Documentation and Examples

[JSDoc page](http://dylanfprice.github.com/angular-gm/dist/docs/) (this README)

[AngularGM Module](http://dylanfprice.github.com/angular-gm/dist/docs/module-AngularGM.html)


## Development

Clone the repo, `git clone git://github.com/dylanfprice/angular-gm.git`

AngularGM is tested with `karma`

``` bash
$ sudo npm install grunt-cli --global
$ npm install --dev
$ grunt karma:server
```

You can build the latest version using `grunt`.

``` bash
$ grunt build
```


## Author

**Dylan Price** (http://github.com/dylanfprice)


## Credits

Inspired by Nicolas Laplante's angular-google-maps directive (http://github.com/nlaplante/angular-google-maps)

README and project layout stolen from Olivier Louvignes' AngularStrap repo (http://github.com/mgcrea/angular-strap)
  
