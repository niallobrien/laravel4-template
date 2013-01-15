## Laravel 4 Starter Template

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

This is a good starting point for Laravel 4 projects as I've included some extra helpful packages (more on this later).

#####Install Composer inside your project directory.
		curl -s http://getcomposer.org/installer | php

#####Install all required packages.
		php composer.phar install

#####Git to work! :)

### Added Packages
1. Meido/Form
2. Meido/HTML
3. bigelephant/string

Included are [Meido](https://github.com/meido)'s Form and HTML classes, which are direct ports from Laravel 3.
[Really Big Elephant](https://github.com/bigelephant/) released a nice [String](https://github.com/bigelephant/string) class, that does much more than a port of Str released by Meido, so that's included here instead. Note, the class alias is **String** not **Str** as you may be used to from Laravel 3.

### Contributing To Laravel

**All issues and pull requests should be filed on the [laravel/framework](http://github.com/laravel/framework) repository.**

### License

The Laravel framework is open-sourced software license under the [MIT license](http://opensource.org/licenses/MIT)