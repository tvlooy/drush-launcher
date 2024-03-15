# Drush launcher

This is a simple bash alternative for drush launcher.

## Install

```
curl -o /usr/local/bin/drush https://raw.githubusercontent.com/tvlooy/drush-launcher/master/drush
chmod +x /usr/local/bin/drush
```

## Xdebug compatibility

Drush Launcher, like Composer automatically disables Xdebug by default. This improves performance substantially. You may override this feature by setting an environment variable. ``DRUSH_ALLOW_XDEBUG=1 drush [command]``
