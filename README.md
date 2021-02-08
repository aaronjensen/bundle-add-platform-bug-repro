```sh
bundle cache --all-platforms
```

## Expected

- `Gemfile.lock` is not modified
- `vendor/cache` includes linux versions

## Actual

- `Gemfile.lock` is modified, with linux versions removed
- `vendor/cache` does not include linux versions
