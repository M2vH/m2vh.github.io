---
layout: post
title: "Serve GitHub Jekyll locally"
category: jekyll
tags: jekyll github pages m2vh
---

# {{ page.title }}

Date: {{ page.date }}

Guess, we want to debug a GitHub website locally. Therefore I installed Jekyll for Windows.

About `How to install Ruby on Windows` is topic of another post.

---

### Add a `Gemfile` to repository

We need some Ruby gems locally. We add a `Gemfile` with the following content:

```rb
# file: ./Gemfile

source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins
```

Then we run `bundle install`.

Now we receive a bunch of gems, including the build-in `themes` for GitHub pages. 

### Add a branch to repository

Because I want to check everything locally before pushing to `origin/master` I created a seperate branch `serveLocally`.

### Command to build the local GitHub page

- checkout `serveLocally` branch

```bash
bundle exec jekyll serve
```

I can reach the GitHub page locally at `localhost:4000`.

---

Next step is switching back to `master` branch, merge the `serveLocally` and `push` to GitHub.

---
