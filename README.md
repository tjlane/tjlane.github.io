# TJL Personally Hosted Website

![pages-build-deployment](https://github.com/tjlane/tjlane.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)

Forked from academic pages -- thanks!

## Running Locally

    On MacOS the commands are:
    ```bash
    brew install ruby
    brew install node
    gem install bundler
    ```
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `jekyll serve -l -H localhost` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.
