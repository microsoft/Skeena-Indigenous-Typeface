# Documentation

This documentation site is built using [Jekyll](https://github.com/jekyll/jekyll) and a customized version of the [Just the Docs theme](https://github.com/just-the-docs/just-the-docs).

Each time changes are made to files in this `docs/` folder, it’s build and deployed using GitHub Actions.

## Local development

It’s not necessary to run the entire documentation site locally to make changes to the content. Content changes can be made to the Markdown files either by editing the files locally or directly on GitHub.

Otherwise, with Ruby and Bundler installed, you can run the project locally with the following commands:

```sh
cd ./docs
bundle install
bundle exec jekyll serve
```

The site will now be available at `localhost:4000`.
