
# Academic Pages

![pages-build-deployment](https://github.com/academicpages/academicpages.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)

Academic Pages is a Github Pages template for academic websites.


## Running Locally

1. Run `bundle exec jekyll serve -l -H localhost` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.

## Notes:

1. Change the colors of the links in `_sass/_variables.scss`
1. Change the header from Bold to Normal in `_sass/_base.scss`

### Deploy on Cloudflare pages:

1. `bundle update`: Update `Gemfile` and `Gemfile.lock`. Commit both of them, so that the dependencies are explicitly resolved. Source: https://developers.cloudflare.com/pages/migrations/migrating-jekyll-from-github-pages/
2. In Cloudflare, build with command `bundle exec jekyll build`
3. In Cloudflare, set environment variable `LC_ALL=C.UTF-8`. Source: https://herrickfang.com/2023/11/26/cloudflare-workers/