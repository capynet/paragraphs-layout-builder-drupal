# Setup project
* Get source code `ddev composer install`
* Install the site `ddev drush site:install --db-url=mysql://db:db@ddev-paragraphs-layout-builder-db/db --account-pass=admin -y`

## Useful info:
User/pass: `admin`/`admin`

Since this site if for integrating paragraphs-layout-builder module, every time you need a fresh version of it, use `ddev composer require capynet/paragraphs-layout-builder --no-cache`