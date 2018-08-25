# Tufthaven

The intent of this theme is to adapt [Tufte CSS](https://edwardtufte.github.io/tufte-css/) styling for a [Posthaven](https://posthaven.com/) site.

## Theme Building Resources

* [Posthaven theme documentation](http://theme-docs.posthaven.com/)
* See the [posthaven_theme](https://github.com/posthaven/posthaven_theme) gem for theme file upload via the API.
* [Liquid documentation](https://www.shopify.com/partners/blog/115244038-an-overview-of-liquid-shopifys-templating-language)
* [Tufte CSS source](https://github.com/edwardtufte/tufte-css)

## Building Assets

### Install Gems

Install [bundler](http://bundler.io) and run:
```
bundle install
```

### Building SCSS

Build `assets/blog.css`:
```
rake compile
```

Watch `src/blog.scss` and build on update:
```
rake watch
```
