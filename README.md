# Grace Framework

[![Build Status](https://travis-ci.org/slimphp/Slim.svg?branch=master)](https://travis-ci.org/slimphp/Slim)

Slim is a PHP micro framework that helps you quickly write simple yet powerful web applications and APIs.
Slim is easy to use for both beginners and professionals. Slim favors cleanliness over terseness and common cases
over edge cases. Its interface is simple, intuitive, and extensively documented — both online and in the code itself.
Thank you for choosing the Slim Framework for your next project. I think you're going to love it.

## Features

* Powerful router
    * Standard and custom HTTP methods
    * Route parameters with wildcards and conditions
    * Route redirect, halt, and pass
    * Route middleware
* Resource Locator and DI container
* Template rendering with custom views
* Flash messages


### Highlights

- Simple API
- [RFC3986](http://tools.ietf.org/html/rfc3986) compliant
- Implements the `UriInterface` from [PSR-7][]
- Fully documented
- Framework Agnostic
- Composer ready, [PSR-2][] and [PSR-4][] compliant



### Documentation

Full documentation can be found at [url.thephpleague.com](http://url.thephpleague.com). Contribute to this documentation in the [gh-pages](https://github.com/thephpleague/url/tree/gh-pages) branch

# Getting Started






### System Requirements

You need:

- **PHP >= 5.5.0** , but the latest stable version of PHP is recommended
- the `mbstring` extension
- "league/url": "^3.3"

To use the library.

### Install

You may install the Slim Framework with Composer (recommended) or manually.

[Read how to install Slim](http://docs.slimframework.com/#Installation)

Install `shampeak\request` using Composer.

```
$ composer require shampeak/request
```

### Testing

`League\Uri` has a [PHPUnit](https://phpunit.de) test suite and a coding style compliance test suite using [PHP CS Fixer](http://cs.sensiolabs.org/). To run the tests, run the following command from the project folder.

``` bash
$ composer test
```

### Use

```
//$req = new Sham\Http\Request(Sham\Environment::getInstance());
$req = new Sham\Request() ;
$get = $req->get();                     //GET数据
$path1 = $req->getPath();               //path数据
$path2 = $req->getPath()->toArray();    //path数组
```










## How to Contribute


*NOTE: We are only accepting security fixes for Slim 2 (master branch). All development is concentrated on Slim 3 which is on the develop branch.*


### Pull Requests

1. Fork the Slim Framework repository
2. Create a new branch for each feature or improvement
3. Send a pull request from each feature branch to the **develop** branch

It is very important to separate new features or improvements into separate feature branches, and to send a pull
request for each branch. This allows me to review and pull in new features or improvements individually.

### Style Guide

All pull requests must adhere to the [PSR-2](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md) standard.

### Unit Testing

All pull requests must be accompanied by passing unit tests and complete code coverage. The Slim Framework uses
`phpunit` for testing.

[Learn about PHPUnit](https://github.com/sebastianbergmann/phpunit/)

## Community

### Forum and Knowledgebase

Visit Slim's official forum and knowledge base at <http://help.slimframework.com> where you can find announcements,
chat with fellow Slim users, ask questions, help others, or show off your cool Slim Framework apps.

### Twitter

Follow [@slimphp](http://www.twitter.com/slimphp) on Twitter to receive news and updates about the framework.









## Contributing

Contributions are welcome and will be fully credited. Please see [CONTRIBUTING](CONTRIBUTING.md) and [CONDUCT](CONDUCT.md) for details.

## Security

If you discover any security related issues, please email shampeak@sina.com instead of using the issue tracker.

## Author

The Slim Framework is created and maintained by [Josh Lockhart](http://www.joshlockhart.com). Josh is a senior
web developer at [New Media Campaigns](http://www.newmediacampaigns.com/). Josh also created and maintains
[PHP: The Right Way](http://www.phptherightway.com/), a popular movement in the PHP community to introduce new
PHP programmers to best practices and good information.

## License

The Grace Framework is released under the MIT public license.
Please see [License File](LICENSE) for more information.

[PSR-2]: http://www.php-fig.org/psr/psr-2/
[PSR-4]: http://www.php-fig.org/psr/psr-4/
[PSR-7]: http://www.php-fig.org/psr/psr-7/
