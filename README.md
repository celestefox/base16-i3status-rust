# base16-i3status-rust

This is a repository that provides a [base16](https://github.com/chriskempson/base16) template to generate theme
settings for [i3status-rust](https://github.com/greshake/i3status-rust).

To use, just pick a config snippet from colors/ and put it in your i3status-rust configuration, however you want.

The theme is "based" on the Solarized Dark builtin theme in i3status-rust. This is mostly because the plain theme,
which otherwise I would have used, doesn't use the powerline character for a separator.

The colors were chosen based on what [base16's website](http://chriskempson.com/projects/base16/) says about the
colors (both the example shades in the list saying what the colors are meant to be used for and _what_ it says they
are used for) and the colors of Solarized that the builtin theme chose. This is more optimised for dark themes, as a
result, so I may add another template that should work better for light themes. I'm also 100% open to switching around
what color goes where.

As a final note, if you want to be able to easily switch, because i3status-rust has no "include" mechanism, I
recommend checking out [base16-builder-python/pybase16](https://github.com/InspectorMustache/base16-builder-python)
and its `inject`.
