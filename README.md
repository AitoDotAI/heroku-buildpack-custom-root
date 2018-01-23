# heroku-buildpack-custom-root

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Highly experimental buildpack which allows deploying a single directory from a mono repository.

## Usage
1. Add the buildpack to be the first:

        $ heroku buildpacks add https://github.com/SectorLabs/heroku-buildpack-custom-root

2. Set a configuration variable pointing to the directory in your repository that you want to deploy:

        $ heroku config:set ROOT_DIR=subdir/

3. Enjoy
