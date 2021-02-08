```
bundle lock --add-platform x86_64-linux
```

## Actual

```
Fetching gem metadata from https://rubygems.org/.
Resolving dependencies...
Bundler found conflicting requirements for the Ruby version:
  In Gemfile:
    Ruby

    raygun-apm was resolved to 1.0.78, which depends on
      Ruby (< 2.8.dev, >= 2.5)
```

## Expected

No error
