# Setup project

- Get source code `ddev composer install`
- Install the site `ddev drush site:install --db-url=mysql://db:db@ddev-paragraphs-layout-builder-db/db --account-pass=admin -y`
- Enable needed modules: `ddev drush en admin_toolbar merlb -y`

## Useful info:

User/pass: `admin`/`admin`

### Developing:

If you are developing uncomment `web/sites/default/settings.php` to invalidate cache layers to avoid unexpected behaviors.
