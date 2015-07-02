# bootstrap-chosen (less)

![Example dropdown](https://raw.githubusercontent.com/CjS77/bootstrap-chosen/master/example.png)

An alternate stylesheet for [Chosen 1.0](http://harvesthq.github.com/chosen/). This
one is supposed to integrate better with [Bootstrap 3.0](http://getbootstrap.com/).

It uses font-awesome rather than sprites.

How to
======

* Install

        $ bower install --save chosen-bootstrap3-fontawesome

* In your main less file:

        @import 'path_to_bootstrap_less_files/variables.less';
        @import 'path_to_bootstrap_less_files/mixins.less';
        @import 'path_to_chosen-bootstrap3-fontawesome/bootstrap-chosen.less'

Then compile your less as part of your build process
                
**OR** to use the precompiled .css

        <link rel="stylesheet" href="path_to_chosen-bootstrap3-fontawesome/bootstrap-chosen.css" />


Prerequisites
=============

https://github.com/twitter/bootstrap/
https://github.com/FortAwesome/Font-Awesome

License: [MIT](https://en.wikipedia.org/wiki/MIT_License)

