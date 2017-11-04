## The Vue2 with Semantic UI for Laravel 5.5

- Starter kit Vue2 in conjunction with Semantic UI for Laravel 5.5
 
## Installation

```sh
$ laravel new project && cd project/
$ composer require peter58228/laravel-vue-semantic-ui
```

Then add to config/app.php
```php
Peter58228\VueSemanticUi\VueSemanticUiServiceProvider::class,
```

Then
```sh
$ php artisan vendor:publish --force --provider="Peter58228\VueSemanticUi\VueSemanticUiServiceProvider"
$ npm install && npm run dev-ui
```

## License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
