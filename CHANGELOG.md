All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).


## Unreleased

### Breaking changes

-

### Compatible changes

-

## 0.14.1 - 2017-11-13

### Compatible changes

- inherit power guards upon controller inheritance (fixes #40)

## 0.14.0 - 2017-10-09

### Breaking changes

- drop support for Rails 2.3

### Compatible changes

- migrate tests to Gemika

## 0.13.2 - 2017-10-02

### Compatible changes

- Bang methods should return the scope when successful (e.g. `power.notes!` returns the scope you defined in the power)
- improve the error message for scoped powers

## 0.13.1 - 2017-09-28

### Compatible changes

- Fix controller integration when using `ActionController::API`.

Thanks to derekprior.


## 0.13.0 - 2017-09-05

### Breaking change

- All powers memoize.


## Older releases

Please check commits.

