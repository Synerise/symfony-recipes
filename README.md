# Synerise Symofony Recipes

Symfony Flex recipes repository for bundles provided by Synerise.

### Usage

```bash
composer config --json --merge extra.symfony.endpoint '["https://api.github.com/repos/synerise/symfony-recipes/contents/index.json?ref=flex/main"]'
```

Alternatively, edit `composer.json` file of your application to include an endpoint of Synerise recipes repository:

```json
    "extra": {
        "symfony": {
            "endpoint": [
                "https://api.github.com/repos/synerise/symfony-recipes/contents/index.json?ref=flex/main",
                "..."
            ]
        }
        "..."
    }
```
