# Exercise Edisyst Stubs package

In the **composer.json** add this

    "autoload-dev": {
        "psr-4": {
            "Tests\\": "tests/",
            "Edisyst\\Simplestubs\\": "packages/edisyst/simplestubs/src"
        }

In the **app/config.php** add the provider

        Edisyst\Simplestubs\SimplestubsServiceProvider::class,

## Usage

    php artisan edisyst-stub:publish
