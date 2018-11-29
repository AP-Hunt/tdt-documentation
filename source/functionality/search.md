# Enable search

The search function is especially useful for multipage documentation.

## Amend the tech-docs.yml file

Add the following to the end of your project’s `.../config/tech-docs.yml` file, or set it to true if it is already there:

```
# Enable search
enable_search: true
```

Add the following to your `REPO/Gemfile`:

```
gem 'govuk_tech_docs'
gem 'middleman-search-gds'
```

For example:

```
source 'https://rubygems.org'

# For faster file watcher updates on Windows:
gem 'wdm', '~> 0.1.0', platforms: [:mswin, :mingw]

# Windows does not come with time zone data
gem 'tzinfo-data', platforms: [:mswin, :mingw, :jruby]

gem 'govuk_tech_docs'
gem 'middleman-search-gds'
```

