## Usage

### Add recipes repository

In `composer.json` file of you application add enpoint our recipes repository: `https://api.github.com/repos/synerise/symfony-recipes/contents/index.json`.

Minimal config:

```json
    "symfony": {
        "endpoint": [
            "https://api.github.com/repos/synerise/symfony-recipes/contents/index.json",
            "flex://defaults"
        ]
    }
```

### Private repository

Follow the [guidelines]("https://api.github.com/repos/synerise/symfony-recipes/contents/index.json") to grant composer access to the repository.

