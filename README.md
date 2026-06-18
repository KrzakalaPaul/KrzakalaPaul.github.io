# Paul Krzakala's academic website

Personal academic website published at
[krzakalapaul.github.io](https://krzakalapaul.github.io/). It is built with
Jekyll and based on the [Academic Pages](https://academicpages.github.io/)
theme.

## Content

- `_pages/`: homepage and top-level pages
- `_publications/`: publication records
- `_talks/`: talks and presentations
- `_teaching/`: teaching records
- `_data/`: navigation, author, interface, and retained site data
- `files/`: papers, slides, notebooks, and other downloads
- `images/`: profile and site images

## Local development

Install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve --livereload
```

The local site is available at <http://localhost:4000>.

## Updating the site

Site-wide settings are in `_config.yml`, navigation is in
`_data/navigation.yml`, and publication/talk helper scripts are in
`markdown_generator/`.
