### install prerequisites

```
sudo apt install ruby-dev ruby-rubygems
gem install jekyll bundler
```

### create blog

```
jekyll new myblog
cd myblog
```

### deploy to github pages

Following the instructions from [here](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll) isn't necessary, but recommended for testing locally. I haven't done it here.

### run locally

```
cd /path/to/here
bundle exec jekyll serve --livereload
```

## changing layout

check the theme name in _config.yml: `minima`

```
bundle info --path minima
```

Copy the things you want to modify, from that path to this path.
