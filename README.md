# Pneumatic

Pneumatic is a minimalistic, single-author [Pelican][pelican] theme derived from
a [theme][simply] developed by [Greg Reda][greg-reda]. It was named due to the
fact that it is based on the [Skeleton][skeleton] framework, and pelicans
(like most birds) possess [skeletal pneumaticity][pneumaticity]. Visit
**[kevinyap.ca][kevinyap.ca]** to see Pneumatic in action.

## Requirements

- [Assets][assets] plugin (and [webassets][webassets])
- [Neighbors][neighbors] plugin
- [Sass][sass]

## Configuration

- Create a directory containing all of the [relevant icons][icons]. Set
  `ICONS_PATH` to that directory's path (ex. `images/icons`) and ensure that
  it has been added to `STATIC_PATHS`.
- There are intentionally no author, category, and tag page templates, so
  `AUTHORS_SAVE_AS`, `CATEGORY_SAVE_AS`, `CATEGORIES_SAVE_AS`, and
  `TAGS_SAVE_AS` should all be set to `''`.
- [`pygments.css`][pygments.css] can be modified to change the syntax
  highlighting colour scheme.
- CodeHilite line numbers should be enabled in Pelican's configuration file:

  ```python
  MD_EXTENSIONS = [codehilite(linenums=True)]
  ```

- Some font and colour choices can be customized in [`pneumatic.scss`][pneumatic.scss].

Here are theme-specific settings that should be present in the Pelican configuration file:

|  Setting            | Description                                            |
|:-------------------:|--------------------------------------------------------|
| `SITENAME`          | Text displayed under avatar in sidebar                 |
| `BIO_TEXT`          | Text displayed under site name                         |
| `FOOTER_TEXT`       | Text displayed in site footer                          |
| `ICONS_PATH`        | Location of site icons (ex. `images/icons`)            |
| `SITE_AUTHOR`       | Used for author `<meta>`                               |
| `TWITTER_USERNAME`  | Used for Twitter Cards `<meta>`                        |
| `GOOGLE_PLUS_URL`   | Used for Google+ `<meta>`                              |
| `INDEX_DESCRIPTION` | Used for description `<meta>` on index page            |
| `SIDEBAR_LINKS`     | List of anchor elements to be displayed under bio text |
| `GOOGLE_FONTS`      | List of fonts to import from Google Fonts              |
| `SOCIAL_ICONS`      | List of tuples in the form `(link, title, icon-class)` |
| `DISQUS_SITENAME`   | Disqus shortname (optional)                            |
| `GOOGLE_ANALYTICS`  | Google Analytics tracking code (optional)              |
| `DOMAIN`            | Used for Google Analytics and Twitter Cards `<meta>`   |


## Screenshots

![Index Page](screenshots/index.png?raw=true)
![Article](screenshots/article.png?raw=true)

## License

Pneumatic is licensed under the [MIT License][mit-license].

[pelican]: http://getpelican.com
[simply]: https://github.com/gjreda/gregreda.com/tree/master/theme/simply
[greg-reda]: http://www.gregreda.com
[skeleton]: http://getskeleton.com
[pneumaticity]: http://en.wikipedia.org/wiki/Skeletal_pneumaticity
[kevinyap.ca]: http://kevinyap.ca

[assets]: https://github.com/getpelican/pelican-plugins/tree/master/assets
[webassets]: https://github.com/miracle2k/webassets
[neighbors]: https://github.com/getpelican/pelican-plugins/tree/master/neighbors
[sass]: http://sass-lang.com

[icons]: https://github.com/iKevinY/iKevinY.github.io/tree/src/content/images/icons
[pygments.css]: static/pygments.css
[pneumatic.scss]: static/pneumatic.scss

[mit-license]: https://github.com/iKevinY/EulerPy/blob/master/LICENSE
