ng-datepicker
===========
[ng-datepicker] AngularJs Datepicker based on jQuery UI

<p>
  <img src="https://img.shields.io/badge/ng--datepicker-release-green.svg">
  <img src="https://img.shields.io/badge/version-beta-blue.svg">
  <img src="https://img.shields.io/bower/v/bootstrap.svg">
  <img src="https://img.shields.io/github/license/mashape/apistatus.svg">
</p>

<h3>Implementation</h3>
```
<ng-datepicker ng-name="effectiveBeginning" ng-required="true" ng-model="effectiveBeginning" dateFormat="dd/mm/yy" minDate="-15D" maxDate="+1M +10D" buttonImage="images/ico-calendario.png" buttonText="Show calendar" ng-class="" native-class="form-control input-text"></ng-datepicker>
```

## Bower install de dependency
```
$ bower install ng.datepicker-ui --save
```

## Module AngularJS include
```
angular.module('example', ["ngDatepicker"]);
```

## CSS compatibility with bootstrap
```
<!-- build:css(.) styles/style.css -->
<!-- bower:css -->
  <link rel="stylesheet" href="bower_components/jquery-ui-bootstrap/jquery.ui.theme.css" />
<!-- endbower -->
<!-- endbuild -->

<!-- build:css(.tmp) styles/main.css -->
  <link rel="stylesheet" href="bower_components/jquery-ui/themes/base/jquery-ui.css" />
  <link rel="stylesheet" href="bower_components/jquery-ui-bootstrap/jquery.ui.theme.font-awesome.css" />
<!-- endbuild -->
```
