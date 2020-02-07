# Planraum website

This repository hold the planraum website.

TravisCI Status: [![Build Status](https://travis-ci.com/iptizer/planraum.github.io.svg?branch=master)](https://travis-ci.com/iptizer/planraum.github.io)

## Prerequisits

* Install ruby & gem & bundler
* Install gems from Gemfile

On a Mac:

```sh
brew install ruby
bundle update
bundle install
```

## Adding new content

Adding new content requires to add a new feature branch and create a pull request. This pull request has to be accepted by a Planraum colleague. Don't worry, it's not that complicated!

```sh
# Assuming you're in branch master
# Create a branch with a name that describes your changes
BRANCH_NAME="my_cool_new_content"
git checkout -b $BRANCH_NAME
# Make your changes. You can start a local dev server using bundle.
bundle exec jekyll serve
# Add your changes to the repository
git add .
git commit -m "Describe your change in the message"
git push --set-upstream origin $BRANCH_NAME
```

Now open a pull request via [the GitHub compare function]{https://github.com/planraum/planraum.github.io/compare}. Select your branch on the right side. Verify your changes. And click on "Create Pull Request".