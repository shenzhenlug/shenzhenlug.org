# jekyll-theme-console

A jekyll theme with inspiration from linux consoles for hackers, developers and script kiddies.


## Demo

[https://b2a3e8.github.io/jekyll-theme-console/](https://b2a3e8.github.io/jekyll-theme-console/)


## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-theme-console"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: jekyll-theme-console
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jekyll-theme-console

## Usage

In addition to jekyll's default configuration options, you can provide:
- `header_pages` to specify which pages should be displayed in navbar
- `footer` string, which will be inserted on the end of the page (doesn't support markup, but html)
- `google_analytics` tracking id (tracking will be enabled only in production environments)

```yaml
header_pages:
  - index.md
  - about.md

footer: 'follow us on <a href="https://twitter.com/xxx">twitter</a>'

google_analytics: UA-NNNNNNNN-N
```


## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/b2a3e8/jekyll-theme-console. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
