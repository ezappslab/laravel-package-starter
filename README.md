# Laravel Package Starter

This is a robust skeleton starter kit designed to simplify the creation of new Laravel packages. It provides a foundation with pre-configured tools and best practices to help you focus on building your package functionality efficiently.

## Getting Started

To bootstrap your package, replace the placeholders and use this prompt with your preferred AI assistant:

```text
Customize this Laravel package starter using the following metadata:

Composer package: {{ vendor }}/{{ package-name }}
PHP namespace: {{ Vendor\PackageName }}
Package name: {{ package-name }}
Service provider: {{ PackageName }}ServiceProvider

Update every starter-specific identifier consistently, including:

- Composer package metadata, PSR-4 autoloading, and Laravel provider discovery.
- The service provider namespace, class name, package name, and install command.
- Source and test references, filenames, configuration, documentation, and workbench
  integration where applicable.

Use kebab-case for Composer and package names, StudlyCase for PHP symbols, and the
provided namespace exactly. Do not replace unrelated uses of words such as "example"
(for example, example.com email addresses).

Preserve the existing Laravel 12/13 compatibility and development tooling. Remove all
starter placeholders and obsolete example identifiers, regenerate Composer autoloading,
then run Composer validation, formatting, static analysis, and tests. Report the files
changed and any checks that could not be completed.
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
