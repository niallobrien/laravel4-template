## Laravel 4.x
=======
### A Framework For Web Artisans

[Official Documentation](http://four.laravel.com) (Under Active Development)

### Starter Template Usage
This starter template is designed to get you up and going with Laravel 4 as quickly as possible.
Laravel 4 has removed certain functionality that was available in Laravel 3. The reason was due to duplication of work.

This package includes these "missing features".

Now that Laravel 4 is using Composer (php equivalent of node's NPM or Ruby's RVM), you can add any required functionality to your app via Composer packages (Laravel itself is a Composer package and so are its dependencies).
  
#####Clone the Laravel 4 Starter Template wherever you want to start your project.

		git clone https://github.com/niallobrien/laravel4-template.git name-of-project
		cd name-of-project

This is a good starting point for Laravel 4 projects.

#####Install Composer inside your project directory.
		curl -s http://getcomposer.org/installer | php

#####Install all required packages.
		php composer.phar install

#####Git to work! :)

### Added Packages
1. raveren/kint
2. PHPunit

dd() is no longer available in L4, so I've included [Kint](https://github.com/raveren/kint) which is a great debugging helper.

For running tests, [PHPunit](https://github.com/sebastianbergmann/phpunit/) is required, so I've added it to dev. To install, run:
		
		php composer.phar install --dev
		
Then within your project directory, run 'phpunit' (without quotes) to run the example tests included with L4.
See the [Unit testing L4 docs](http://four.laravel.com/docs/testing) for more info. 
	
=======
### Contributing To Laravel

**All issues and pull requests should be filed on the [laravel/framework](http://github.com/laravel/framework) repository.**

### License

The Laravel framework is open-sourced software license under the [MIT license](http://opensource.org/licenses/MIT)
