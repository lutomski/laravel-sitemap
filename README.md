### **The package was created only because the official one was not compatible with laravel 9.**

#### Official package: https://github.com/Laravelium/laravel-sitemap

## Installation

Run the following command and provide the latest stable version (e.g v8.\*) :

```bash
composer require lutomski/laravel-sitemap
```

*or add the following to your `composer.json` file :*

#### For Laravel 9
```json
"lutomski/laravel-sitemap": "^9.*"
```

*Publish needed assets (styles, views, config files) :*

```bash
php artisan vendor:publish --provider="Laravelium\Sitemap\SitemapServiceProvider"
```
