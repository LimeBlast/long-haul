# What I'm Doing to Prepare for the Zombie Apocalypse

A Jekyll blog, based on the [Long Haul theme](https://github.com/brianmaierjr/long-haul).

## Setup

1. [Install Jekyll](http://jekyllrb.com)
2. Fork the [Long Haul repo](http://github.com/brianmaierjr/long-haul)
3. Clone it
4. [Install Bundler](http://bundler.io/)
5. Run `bundle install`
6. Install gulp dependencies by running `npm install`
7. Run Jekyll and watch files by running `bundle exec gulp`
8. Customize and watch the magic happen!

## Site Settings

The main settings can be found inside the `_config.yml` file:

- **title:** title of your site
- **description:** description of your site
- **url:** your url
- **paginate:** the amount of posts displayed on homepage
- **navigation:** these are the links in the main site navigation
- **social** diverse social media usernames (optional)
- **google_analytics** Google Analytics key (optional)


## Creating new posts

[Jekyll::Compose](https://github.com/jekyll/jekyll-compose) is used to provide a quick way of composing new posts via the CLI, eg:

```bash
$ bundle exec jekyll page "My new page"
$ bundle exec jekyll post "My new post"
$ bundle exec jekyll draft "My new draft"
$ bundle exec jekyll publish _drafts/my-new-draft.md
```

## License

This is [MIT](LICENSE) with no added caveats, so feel free to use this Jekyll theme on your site without linking back to me or using a disclaimer.
