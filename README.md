# nathan-weinberg.github.io

Personal website that can be found at [nathanweinberg.me](https://nathanweinberg.me/)

## To Run Locally
These instructions assume the use of Fedora Linux. It is **highly recommended** that you use [rvm](https://rvm.io). Ensure you are using Ruby 2.7.

### Initial Setup
- Install requirements if you haven't already: https://jekyllrb.com/docs/installation/
- Install prerequisites if you haven't already: https://jekyllrb.com/docs/installation/other-linux/
- Install the jekyll and bundler gems if you haven't already: https://jekyllrb.com/docs/installation/ubuntu/

Then run the following command within the project directory:
```bash
$ bundle install
```

### Running
Run the following commands within the project directory:
```bash
$ bundle update github-pages
$ bundle exec jekyll serve
```

## Templating

Currently the site uses the [Cayman Jekyll theme](https://github.com/pages-themes/cayman)

## Form Submission

Currently the site uses [Formspree](https://formspree.io/) for the Contact section
