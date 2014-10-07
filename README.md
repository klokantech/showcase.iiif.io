[![Build Status](https://travis-ci.org/IIIF/iiif.io.svg?branch=master)](https://travis-ci.org/IIIF/iiif.io)

# IIIF Showcase

Source of the IIIF demos site (showcase.iiif.io)

## To Debug the Site

 1. `bundle install`

 2. Run `$ ./dev.sh` to compile the site and run a dev server on [http://localhost:4000](http://localhost:4000).

## To Publish the Site

(E.g. for Apache to serve), run `./publish.sh /my/site/dir`. Note that if the site is not at '/' on the server, js and css will not work (the source files use absolute paths.)

## Some Things to Note

 * Much of the site data is in the YAML files in `_data/` make edits there.
 * Site level variables are set in  `_config.yml`.
