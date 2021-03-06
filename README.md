This is the source for "FOLIO Developers" at folio-org.github.io
which is [dev.folio.org](http://dev.folio.org/)

To contribute changes, please make the changes in a new branch and submit a
pull request.

Local development requires [Ruby](https://www.ruby-lang.org/) and
[Bundler](https://bundler.io/).
The 'bundle install' step will install the relevant local
[Jekyll](https://jekyllrb.com/).

For Ruby, using [rbenv](https://github.com/rbenv/rbenv) and its 'ruby-build'
plugin ensures a smooth process. In this directory, set the ruby version
with: `rbenv local <version>`

Then do:

```
bundle install --path vendor/bundle
```

```
bundle exec jekyll serve --port 5000
```

```
bundle exec jekyll build
```

Occasionally do `bundle update` to advance the versions of dependencies.

## Work area - management of dev site

See [notes](work/README.md).

## Theme enhancements

If there is a need to override any more files, then copy them from the theme.
To find them, do: `bundle show minima`

## Regenerate ToC

To regenerate the Table of Contents for some files, see instructions above its ToC.
Then replace the ToC with the generated output.

## Deployment

The master branch is automatically deployed as [dev.folio.org](http://dev.folio.org/)

## Additional information

See project [FOLIO](https://issues.folio.org/browse/FOLIO)
at the [FOLIO issue tracker](http://dev.folio.org/community/guide-issues).
We use the label "devweb".

The FOLIO Slack channel #dev-website
