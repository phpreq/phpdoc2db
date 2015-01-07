# phpdoc2db

Create a database of PHP versions from the PHP manual.

## What Does It Do?

`phpdoc2db` parses the PHP manual's source code and builds up a list of which extensions (classes, functions, constants, etc) exist in which versions of PHP.

This list is used by [phpreq](https://github.com/phpreq/phpreq) to help with working out dependencies for your PHP app.

## How To Install

    composer install

## How To Run

    bin/phpdoc2db

## How To Test

	vendor/bin/phpunit

## How To Contribute

Fork on Github, and then:

	git clone git@github.com:<your-username>/phpdoc2db.git
	cd phpdoc2db
	git checkout -b feature/<your-feature-name>
	git branch --track origin/feature/<your-feature-name>

Work on your changes (please include tests!), and when ready, send a Github pull request against the `develop` branch of the `phpreq/phpdoc2db` project.