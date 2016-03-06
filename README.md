Select2
=======
[![Build Status][travis-ci-image]][travis-ci-status]

Select2 is a jQuery-based replacement for select boxes. It supports searching,
remote data sets, and pagination of results.

<<<<<<< HEAD
To get started, checkout examples and documentation at
https://select2.github.io/
=======
To get started, checkout examples and documentation at http://select2.github.io/select2/
>>>>>>> refs/remotes/origin/stable/3.5

Use cases
---------
* Enhancing native selects with search.
* Enhancing native selects with a better multi-select interface.
* Loading data from JavaScript: easily load items via AJAX and have them
  searchable.
* Nesting optgroups: native selects only support one level of nesting. Select2
  does not have this restriction.
* Tagging: ability to add new items on the fly.
* Working with large, remote datasets: ability to partially load a dataset based
  on the search term.
* Paging of large datasets: easy support for loading more pages when the results
  are scrolled to the end.
* Templating: support for custom rendering of results and selections.

Browser compatibility
---------------------
* IE 8+
* Chrome 8+
* Firefox 10+
* Safari 3+
* Opera 10.6+

Select2 is automatically tested on the following browsers.

[![Sauce Labs Test Status][saucelabs-matrix]][saucelabs-status]

Usage
-----
<<<<<<< HEAD
You can source Select2 directly from a CDN like [JSDliver][jsdelivr] or
[CDNJS][cdnjs], [download it from this GitHub repo][releases], or use one of
the integrations below.
=======
You can source Select2 directly from a CDN like [jsDelivr](http://www.jsdelivr.com/#!select2) or [CDNJS](http://www.cdnjs.com/libraries/select2), [download it from this GitHub repo](https://github.com/select2/select2/tags), or use one of the integrations below.
>>>>>>> refs/remotes/origin/stable/3.5

Integrations
------------
Third party developers have create plugins for platforms which allow Select2 to be integrated more natively and quickly. For many platforms, additional plugins are not required because Select2 acts as a standard `<select>` box.

Plugins

* [Django]
  - [django-easy-select2]
  - [django-select2]
* [Meteor] - [meteor-select2]
* [Ruby on Rails][ruby-on-rails] - [select2-rails]
* [Wicket] - [wicketstuff-select2]
* [Yii 2][yii2] - [yii2-widget-select2]

Themes

- [Bootstrap 3][bootstrap3] - [select2-bootstrap-theme]
- [Flat UI][flat-ui] - [select2-flat-theme]
- [Metro UI][metro-ui] - [select2-metro]

<<<<<<< HEAD
Missing an integration? Modify this `README` and make a pull request back here to Select2 on GitHub.
=======
* [Wicket-Select2](https://github.com/ivaynberg/wicket-select2) (Java / [Apache Wicket](http://wicket.apache.org))
* [select2-rails](https://github.com/argerim/select2-rails) (Ruby on Rails)
* [AngularUI](http://angular-ui.github.io/#ui-select) ([AngularJS](https://angularjs.org/))
* [Django](https://github.com/applegrew/django-select2)
* [Symfony](https://github.com/19Gerhard85/sfSelect2WidgetsPlugin)
* [Symfony2](https://github.com/avocode/FormExtensions)
* [Bootstrap 2](https://github.com/t0m/select2-bootstrap-css) and [Bootstrap 3](https://github.com/t0m/select2-bootstrap-css/tree/bootstrap3) (CSS skins)
* [Meteor](https://github.com/nate-strauser/meteor-select2) (modern reactive JavaScript framework; + [Bootstrap 3 skin](https://github.com/esperadomedia/meteor-select2-bootstrap3-css/))
* [Meteor](https://jquery-select2.meteor.com)
* [Yii 2.x](http://demos.krajee.com/widgets#select2)
* [Yii 1.x](https://github.com/tonybolzan/yii-select2)
* [AtmosphereJS](https://atmospherejs.com/package/jquery-select2)
* [EmberJS](https://github.com/iStefo/ember-select-2)

### Example Integrations

* [Knockout.js](https://github.com/ivaynberg/select2/wiki/Knockout.js-Integration)
* [Socket.IO](https://github.com/ivaynberg/select2/wiki/Socket.IO-Integration)
* [PHP](https://github.com/ivaynberg/select2/wiki/PHP-Example)
* [.Net MVC] (https://github.com/ivaynberg/select2/wiki/.Net-MVC-Example)
>>>>>>> refs/remotes/origin/stable/3.5

Internationalization (i18n)
---------------------------
Select2 supports multiple languages by simply including the right language JS
file (`dist/js/i18n/it.js`, `dist/js/i18n/nl.js`, etc.) after
`dist/js/select2.js`.

Missing a language? Just copy `src/js/select2/i18n/en.js`, translate it, and
make a pull request back to Select2 here on GitHub.

Documentation
-------------
<<<<<<< HEAD
The documentation for Select2 is available
[through GitHub Pages][documentation] and is located within this repository
in the [`docs` folder][documentation-folder].
=======

The documentation for Select2 is available [through GitHub Pages](http://select2.github.io/select2/) and is located within this repository in the [`gh-pages` branch](https://github.com/ivaynberg/select2/tree/gh-pages).
>>>>>>> refs/remotes/origin/stable/3.5

Community
---------
You can find out about the different ways to get in touch with the Select2
community at the [Select2 community page][community].

Copyright and license
---------------------
<<<<<<< HEAD
The license is available within the repository in the [LICENSE][license] file.

[cdnjs]: http://www.cdnjs.com/libraries/select2
[community]: https://select2.github.io/community.html
[documentation]: https://select2.github.io/
[documentation-folder]: https://github.com/select2/select2/tree/master/docs
[freenode]: https://freenode.net/
[jsdelivr]: http://www.jsdelivr.com/#!select2
[license]: LICENSE.md
[releases]: https://github.com/select2/select2/releases
[saucelabs-matrix]: https://saucelabs.com/browser-matrix/select2.svg
[saucelabs-status]: https://saucelabs.com/u/select2
[travis-ci-image]: https://img.shields.io/travis/select2/select2/master.svg
[travis-ci-status]: https://travis-ci.org/select2/select2

[bootstrap3]: https://getbootstrap.com/
[django]: https://www.djangoproject.com/
[django-easy-select2]: https://github.com/asyncee/django-easy-select2
[django-select2]: https://github.com/applegrew/django-select2
[flat-ui]: http://designmodo.github.io/Flat-UI/
[meteor]: https://www.meteor.com/
[meteor-select2]: https://github.com/nate-strauser/meteor-select2
[metro-ui]: http://metroui.org.ua/
[select2-metro]: http://metroui.org.ua/select2.html
[ruby-on-rails]: http://rubyonrails.org/
[select2-bootstrap-theme]: https://github.com/select2/select2-bootstrap-theme
[select2-flat-theme]: https://github.com/techhysahil/select2-Flat_Theme
[select2-rails]: https://github.com/argerim/select2-rails
[vue.js]: http://vuejs.org/
[select2-vue]: http://vuejs.org/examples/select2.html
[wicket]: https://wicket.apache.org/
[wicketstuff-select2]: https://github.com/wicketstuff/core/tree/master/select2-parent
[yii2]: http://www.yiiframework.com/
[yii2-widget-select2]: https://github.com/kartik-v/yii2-widget-select2
=======

Copyright 2015 Igor Vaynberg

This software is licensed under the Apache License, Version 2.0 (the "Apache License") or the GNU
General Public License version 2 (the "GPL License"). You may choose either license to govern your
use of this software only upon the condition that you accept all of the terms of either the Apache
License or the GPL License.

You may obtain a copy of the Apache License and the GPL License in the LICENSE file, or at:

http://www.apache.org/licenses/LICENSE-2.0
http://www.gnu.org/licenses/gpl-2.0.html

Unless required by applicable law or agreed to in writing, software distributed under the Apache License
or the GPL License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND,
either express or implied. See the Apache License and the GPL License for the specific language governing
permissions and limitations under the Apache License and the GPL License.
>>>>>>> refs/remotes/origin/stable/3.5
