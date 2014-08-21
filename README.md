# Pneumatic

Pneumatic is a single-author [Pelican](http://getpelican.com) theme derived from a [theme](https://github.com/gjreda/gregreda.com/tree/master/theme/simply) developed by [Greg Reda](http://www.gregreda.com). It was named due to the fact that it is based on the [Skeleton](http://www.getskeleton.com) framework, and pelicans (like most birds) possess [skeletal pneumaticity](http://en.wikipedia.org/wiki/Skeletal_pneumaticity).

## Requirements

- [Assets](https://github.com/getpelican/pelican-plugins/tree/master/assets) plugin
- [Neighbors](https://github.com/getpelican/pelican-plugins/tree/master/neighbors) plugin
- Sass (install via `gem install sass`)

## Configuration

There are no templates for author, category, and tag pages, so `AUTHORS_SAVE_AS`, `CATEGORY_SAVE_AS`, `CATEGORIES_SAVE_AS`, and `TAGS_SAVE_AS` should all be set to `''`. Here are theme-specific settings that should be present in the Pelican configuration file:

|  Setting            | Description                                            |
|:-------------------:|--------------------------------------------------------|
| `SITENAME`          | Text displayed under avatar in sidebar                 |
| `BIO_TEXT`          | Text displayed under site name                         |
| `FOOTER_TEXT`       | Text displayed in site footer                          |
| `SITE_AUTHOR`       | Used for author `<meta>`                               |
| `TWITTER_USERNAME`  | Used for Twitter Cards `<meta>`                        |
| `GOOGLE_PLUS_URL`   | Used for Google+ `<meta>`                              |
| `INDEX_DESCRIPTION` | Used for description `<meta>` on index page            |
| `SIDEBAR_LINKS`     | List of links displayed under bio text                 |
| `SOCIAL_ICONS`      | List of tuples in the form `(link, title, icon-class)` |
| `DISQUS_SITENAME`   | Disqus shortname                                       |
| `GOOGLE_ANALYTICS`  | Google Analytics tracking code                         |


## Screenshots

![Index Page](screenshots/index.png?raw=true)

![Article](screenshots/article.png?raw=true)

![Archive](screenshots/archive.png?raw=true)

<img src="screenshots/mobile.png?raw=true" alt="Mobile" width=420>
