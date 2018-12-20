# Changelog
All notable changes to this project (as a library) will be documented in this file.

This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

Also this project likes fast realizes with even one change to get it live shortly.

## 1.0.0 - 2018-12-21
- Add `options` as last argument to all functions making queries.
- Replace `transaction` function argument with `options`.

## 0.1.0 - 2018-12-19
- Replace arrow functions to 'function'.
- Add `lft` and `rgt` to `getDescendants` function.
- Force `depth` to integer in `getDescendants` and `getAncestors` functions.
- Remove unique modifiers from `lft` and `rgt` column declaration.
- Add options to use different column names for `lft` and `rgt` columns.