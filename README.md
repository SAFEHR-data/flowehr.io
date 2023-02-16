# Introduction
[flowehr.io](https://flowehr.io) is deployed to [GitHub Pages](https://pages.github.com/) and built from the [Minimal Mistakes Jekyll theme](https://mmistakes.github.io/minimal-mistakes/).

# Develop
1. [Setup Ruby](https://www.ruby-lang.org/en/documentation/installation/) in your preferred way
2. Install [bundler](https://bundler.io/) with
```shell
gem install bundler jekyll
```
3. Install dependencies with
```shell
bundle install 
```
4. Clone this repository and change to the workspace directory
5. Build & run with
```shell
bundle exec jekyll serve --livereload
```

## Configuration
- [Theme configuration](https://mmistakes.github.io/minimal-mistakes/docs/configuration/)  
- [Overriding theme defaults](https://mmistakes.github.io/minimal-mistakes/docs/overriding-theme-defaults/)  
- [SASS variables](https://github.com/mmistakes/minimal-mistakes/blob/master/_sass/minimal-mistakes/_variables.scss)

## Troubleshooting
- [GitHub Pages help](https://docs.github.com/en/pages)
- [Setting up a Jekyll site with GitHub Pages](https://jekyllrb.com/docs/github-pages/)
- [Configuring GitHub Metadata](https://github.com/jekyll/github-metadata/blob/master/docs/configuration.md#configuration) to work properly when developing locally and avoid `No GitHub API authentication could be found. Some fields may be missing or have incorrect data.` warnings.