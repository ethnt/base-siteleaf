# base-siteleaf

This is a base template for Siteleaf themes.

## Installation

```
$ bundle install
$ bundle exec siteleaf config [site domain]
```

### Configuration

There are a few site meta variables you can configure:

Variable              | Usage
----------------------|--------------------
`typekit_id`          | For Typekit fonts, add the kit ID and the Typekit embed code will be added to the header of the page.
`google_analytics_id` | If you use Google Analytics, just put in your tracking ID and the code will automatically be added to the bottom of the page.


## Usage

To run the Siteleaf server:

```
$ bundle exec siteleaf server
```

To run Guard to compile assets:

```
$ bundle exec guard
```

To run both at the same time:

```
$ bundle exec foreman start
```
