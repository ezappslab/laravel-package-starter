# Laravel Package Starter

This is a robust skeleton starter kit designed to simplify the creation of new Laravel packages. It provides a foundation with pre-configured tools and best practices to help you focus on building your package functionality efficiently.

## Getting Started

To bootstrap your package development, you can use the following prompt snippet with your favorite AI assistant:

```text
Rename all example code in this Laravel package starter to match:
Vendor: {{ vendor }}
Package: {{ package-name }}
Namespace: {{ Vendor\PackageName }}

Remove placeholders and leave a clean, working package.
```

## Features

- **[spatie/laravel-package-tools](https://github.com/spatie/laravel-package-tools):** Streamlines common tasks in Laravel package development.
- **[Pest](https://pestphp.com):** Elegant and expressive PHP testing framework.
- **[PHPStan](https://github.com/phpstan/phpstan) / [Larastan](https://github.com/nunomaduro/larastan):** Static analysis for catching bugs and enforcing strong typing.
- **[Laravel Pint](https://github.com/laravel/pint):** Opinionated code style fixer.
- **[Orchestra Testbench](https://github.com/orchestral/testbench):** Simulates a Laravel app for package testing.

## Scripts

- `composer lint`: Run Pint and PHPStan.
- `composer test`: Run Pest tests.
- `composer build`: Build workbench assets.
- `composer serve`: Serve the workbench application.

## Documentation

For more detailed information about the included tools, see [docs/tooling.md](docs/tooling.md).
