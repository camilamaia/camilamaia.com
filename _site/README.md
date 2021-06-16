[![Netlify Status](https://api.netlify.com/api/v1/badges/c893a24c-06de-47c9-9e97-e67cc2af1027/deploy-status)](https://app.netlify.com/sites/boring-montalcini-a0bc72/deploys)

# cmaiacd.com

## Tech Stack

- [Jekyll](https://jekyllrb.com)
- Deploys by [Netlify](https://www.netlify.com)

## Install

### Install Ruby

Check if you have Ruby already installed on your machine by running the following command:

```shell
ruby -v
```

If the output is a ruby version, you have it installed on your machine. Otherwise, you need to
install it. [Ruby Installation Doc](https://www.ruby-lang.org/en/downloads/)

### Jekyll

[Install Jekyll](https://jekyllrb.com/docs/installation/):

1. Run the command `gem install bundler jekyll`
2. Check if the installation was successful by running the command `jekyll -v`

## Run

```shell
$ bundle exec jekyll serve
```

## Deploy

This website is hosted on Netlify with an auto deployment enabled i.e whenever any code is merged
into the main branch, a new deployment is triggered.
