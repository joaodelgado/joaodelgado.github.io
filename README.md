# Resume

My resume, heavily based on the great [modern-resume-theme](https://github.com/sproogen/modern-resume-theme).

----

## Running locally

Before you start make sure you have *Ruby* and the gems for *Jekyll* installed locally.
You can find out how to do that [here](https://jekyllrb.com/docs/installation/).

1. Clone your resume repository locally *(if you haven't already)*
2. `cd joaodelgado.github.io`
3. `bundle install`
4. `bundle exec jekyll serve`
5. Open your browser to `http://localhost:4000`

Any changes you make will automatically build and you will be able to see these by refreshing your browser.

*Note: You will need to re-run `bundle exec jekyll serve` to see changes made in `_config.yml`.*

----

### Docker

If you have docker installed you can simply run `docker-compose up` to launch the site in a container, it will then be hosted at `http://localhost:4000`

----

### PDF

Currently I'm using Firefox's print to PDF to generate the PDF version of my CV.
