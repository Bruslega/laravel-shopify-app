# Laravel Shopify App

![Tests](https://github.com/osiset/laravel-shopify/workflows/Package%20Test/badge.svg?branch=master)
[![codecov](https://codecov.io/gh/osiset/laravel-shopify/branch/master/graph/badge.svg?token=qqUuLItqJj)](https://codecov.io/gh/osiset/laravel-shopify)
[![License](https://poser.pugx.org/osiset/laravel-shopify/license)](https://packagist.org/packages/osiset/laravel-shopify)

----

A full-featured Laravel package for aiding in Shopify App development, similar to `shopify_app` for Rails. Works for Laravel 7 and up.

![Screenshot](https://github.com/osiset/laravel-shopify/raw/master/screenshot.png)
![Screenshot: Billable](https://github.com/osiset/laravel-shopify/raw/master/screenshot-billable.png)

## Goals

- [x] Provide assistance in developing Shopify apps with Laravel
- [x] Integration with Shopify API (REST, async REST, GraphQL)
- [x] Authentication & installation for shops (both per-user and offline types)
- [x] Plan & billing integration for single, recurring, and usage-types
- [x] Tracking charges to a shop (recurring, single, usage, etc) with trial support
- [x] Auto install app webhooks and scripttags through background jobs
- [x] Provide basic AppBridge views
- [x] Handles and processes incoming webhooks
- [x] Handles and verifies incoming app proxy requests
- [x] Namespacing abilities to run multiple apps on the same database
