# Laravel Sitemap Package for Laravel 9/10/11

This package, `lutomski/laravel-sitemap`, is designed to provide a compatible and efficient sitemap integration for Laravel versions 9, 10, and 11. It was created in response to compatibility issues with the official Laravelium Sitemap package, ensuring that your application's SEO needs are met without hassle.

## Why `lutomski/laravel-sitemap`?

- **Compatibility:** Specifically tailored for Laravel versions 9, 10, and 11.
- **Ease of Integration:** Quick installation and setup process.
- **Customization:** Ability to publish and customize assets to fit your project's requirements.

### Official Package Reference

For context, here is the original package: [Laravelium Sitemap on GitHub](https://github.com/Laravelium/laravel-sitemap).

## Installation Guide

### Step 1: Install via Composer

To add the sitemap functionality to your Laravel project, run:

```bash
composer require lutomski/laravel-sitemap
```

### Version Specific Instructions

### Step 2: Manual Addition for Specific Versions

Alternatively, manually specify the version in your project's `composer.json` file. Here's how you can do it for different Laravel versions:

| Laravel Version | Package Version             |
|-----------------|-----------------------------|
| Laravel 11      | `"lutomski/laravel-sitemap": "^11.*"` |
| Laravel 10      | `"lutomski/laravel-sitemap": "^10.*"` |
| Laravel 9       | `"lutomski/laravel-sitemap": "^9.*"`  |

### Step 3: Publish Assets

After installation, publish the necessary assets (styles, views, config files) to your project:

```bash
php artisan vendor:publish --provider="Laravelium\Sitemap\SitemapServiceProvider"
```

## Support and Contributions

For support, feature requests, or to contribute, please visit our [GitHub repository](https://github.com/lutomski/laravel-sitemap). Your feedback and contributions are highly appreciated as they help improve this package for the Laravel community.

### TODO:
```
- Complete rewrite of the package
```
