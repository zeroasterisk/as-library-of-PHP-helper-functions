# "as" PHP Helper Library

This is primarily intended as an extension to CakePHP's excellent core libraries ("2.0":http://book.cakephp.org/2.0/en/core-libraries.html "1.3":http://book.cakephp.org/1.3/en/view/1477/Core-Utility-Libraries)


## Installation ##

    git submodule add https://github.com/zeroasterisk/as-library-of-PHP-helper-functions app/Plugin/As

or download and extract to:

    cd path_to_app
    mv as-library-of-PHP-helper-functions Plugin/As

## Configure & Initialize ##

for CakePHP 2.0+ in your App/Config/bootstrap.php file:

    App:uses('Lib', 'As.As');

for CakePHP 1.3+ in your app/configs/bootstrap.php file:

	App::import('lib', 'As.As');

for any other PHP implementation:

    include_once('as.php');

## Basic Usage ##

(WIP)



## License ##

Copyright 2012, [Zeroasterisk](http://zeroasterisk.com)

Licensed under [The MIT License](http://www.opensource.org/licenses/mit-license.php)<br/>
Redistributions of files must retain the above copyright notice.

## Copyright ##

Copyright 2012<br/>
[Zeroasterisk](http://zeroasterisk.com)<br/>
