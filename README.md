# Sous Warp Whistle Recipe

A recipe that contains Sous Warp Whistle configuration.

## Configuring Drupal for Recipes

See <https://www.drupal.org/files/issues/2023-10-01/Configuring%20Drupal%20to%20Apply%20Recipes.md>

## Installing this Recipe

`composer require fourkitchens/sous-warp-whistle`

## Applying this Recipe

If you used the Sous Project as your starterkit:

- `lando install-recipe fourkitchens/sous-warp-whistle`

Manually applying the recipe to your own project: From your webroot run:

- `php core/scripts/drupal recipe recipes/sous-warp-whistle`
- `drush cr`
- `composer unpack fourkitchens/sous-warp-whistle`
