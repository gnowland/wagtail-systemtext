# Wagtail System Text

## Requirements

- Python 2.7 / Python 3.5+
- Django 1.8+
- Wagtail 1.7+


## Installation

Install the library with pip:

```
$ pip install wagtailsystemtext
```



## Quick Setup

Make sure wagtail_geo_widget is added to your `INSTALLED_APPS`.

```python
INSTALLED_APPS = (
    # ...
    'wagtailsystemtext',
)
```

Then add SiteSystemTextMiddleware to your middlewares.

```python
MIDDLEWARE_CLASSES = (
    # ...
    'wagtailsystemtext.middlewares.SiteSystemTextMiddleware',
)
```

Done!


## Roadmap

- [x] `trans" template tag support
- [ ] Wagtail admin view with site permissions
- [ ] Lazy text transforms
- [ ] Cache-rebild on save
- [ ] Sync command between sites
- [ ] Sync command between sites
- [ ] Last accessed timestamps
- [ ] `blocktrans" template tag support
- [ ] Automatic tag discovery


## Contributing

Want to contribute? Awesome. Just send a pull request.


## License

Wagtail-alt-generator is released under the [MIT License](http://www.opensource.org/licenses/MIT).