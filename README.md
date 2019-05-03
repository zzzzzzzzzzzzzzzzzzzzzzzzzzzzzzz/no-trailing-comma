# No trailing comma

Placeholder package for clean diffs in JSON package definition files.

## Usage

### Composer

1. Configure root project to automatically sort packages.
  ```sh
  $ composer config sort-packages true
  ```
  ```json
  "config": {
    "sort-packages": true
  }
  ```

1. Install this package as dependency.
  ```sh
  $ composer require zzzzzzzzzzzzzzzzzzzzzzzzzzzzzzz/no-trailing-comma
  $ composer require --dev zzzzzzzzzzzzzzzzzzzzzzzzzzzzzzz/no-trailing-comma
  ```

### npm

1. Install this package as dependency.
  ```sh
  $ npm install zzzzzzzzzzzzzzzzzzzzzzzzzzzzzzz-no-trailing-comma
  $ npm install --save-dev zzzzzzzzzzzzzzzzzzzzzzzzzzzzzzz-no-trailing-comma
  ```

Notes
* npm sorts packages alphabetically whenever you invoke the commands `install` and `remove`. You can pass the  name of a non-existing package to them to manually sort dependencies in `package.json` once.
