# Upgrading

Because there are many breaking changes an upgrade is not that easy. There are many edge cases this guide does not cover. We accept PRs to improve this guide.

## From 2.0 to 3.0

- `spatie/crawler` is updated to `^3.0`. This version introduced the use of PSR-7 `UriInterface` instead of a custom `Url` class. Please see the [UPGRADING](https://github.com/spatie/crawler/blob/master/UPGRADING.md) guide of `spatie/crawler` to know how to update any custom crawl profiles - if you have any.
