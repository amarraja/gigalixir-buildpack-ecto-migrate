# gigalixir-buildpack-ecto-migrate

Will run migrations for ecto on a gigalixir deploy, and stop the release if migrations fail.

## Usage

Put the following in your .buildbacks file:

```
https://github.com/amarraja/gigalixir-buildpack-ecto-migrate.git
```

Make sure it is after:

```
https://github.com/gigalixir/gigalixir-buildpack-distillery.git
```
