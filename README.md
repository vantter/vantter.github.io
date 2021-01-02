# Vantter.com

Gamifying the game

## Develop

[Install RVM](https://rvm.io/).

Get a compatible Ruby binary:

```
rvm install ruby-2.7
rvm use 2.7
```

Get a compatible bundler:

```
gem install bundler:2.1.4
```

Install dependencies:

```bash
bundle install
```

Run site locally:

```bash
bundle exec jekyll build && bundle exec jekyll s -DIl
```
