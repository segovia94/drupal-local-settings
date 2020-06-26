# Local Drupal Setup

These files are meant to be pulled out individually. The Lando file is all that is needed to get started.

1. Add the `.lando.yml` file to a local Drupal site.

2. Set the Lando `name` to the name of your site

3. Ensure the Lando `webroot` is set to the directory where the Drupal root is located. If it is in the same folder then do `.`.

4. Run `lando drupal-local-settings`. This will pull in the local settings files into your site.

5. Install a fresh site with `lando drupal-install`.
