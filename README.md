
# Landgraf Lab website

## Setup Development

You might need to install [ruby 2.7](https://www.ruby-lang.org/) and then run:

```bash
$ git clone git@github.com:BioroboticsLab/website.git
$ cd website
$ bundle install --path vendor/bundle
$ bundle exec jekyll serve
```

## Add a new person

**Add description:** 
See [`./_people/000_tim_landgraf.html`](/_people/000_tim_landgraf.html) as an
template for a new person. Each file in `./_people` a number prefix to controll
the order in which they are displayed. Lower numbers are on the top (000).
Let's use the following enumeration scheme: (000: Tim, 010: PhD Students, 100: MA/BA Students).

**Add image:** Add your image under `./assets/images`


### Boostrap 4 Github Pages

A [Bootstrap 4](https://getbootstrap.com/) template project for [Github Pages](https://pages.github.com/) and [Jekyll](https://jekyllrb.com/).

* A full Bootstrap 4 theme usable both on Github Pages and with a standalone Jekyll.
* Recompiles Bootstrap from SCSS files, which allows to customize Bootstrap's variables and use Bootstrap themes.
* Full support of Bootstrap's JavaScript plugins.
* Supports all features of Github Pages and Jekyll.

[See the website for demonstration and documentation](https://nicolas-van.github.io/bootstrap-4-github-pages/).

[See the contribution guide.](./CONTRIBUTING.md)

[See the license file.](./LICENSE.md)
