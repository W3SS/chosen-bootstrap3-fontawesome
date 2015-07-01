# bootstrap-chosen (less/sass)

![](https://github.com/alxlit/bootstrap-chosen/raw/master/example.png)

An alternate stylesheet for [Chosen 1.0](http://harvesthq.github.com/chosen/). This
one is supposed to integrate better with [Bootstrap 3.0](http://getbootstrap.com/).

It uses font-awesome rather than sprites.

How to
======

* Clone chosen-bootstrap-fontawesome

        $ git clone https://github.com/marcioAlmada/chosen-bootstrap-fontawesome.git

* Add the following lines to `chosen.less`

        @import 'path_to_bootstrap_less_files/variables.less';
        @import 'path_to_bootstrap_less_files/mixins.less';
    
* Compile `chosen.less`

        $ lessc chosen.less > chosen.css

* You can also do the opposite and import `chosen.less` file inside `bootstrap.less` and compile bootstrap again.

Prerequisites
=============

https://github.com/twitter/bootstrap/
https://github.com/FortAwesome/Font-Awesome

License: [MIT](https://en.wikipedia.org/wiki/MIT_License)

