# WP log
A handy function to write log to uploads/debug.log


# Installation 

## Add these to your wp-config.php

```php
define('WP_DEBUG', true); // To enable debugging. Leave things just like this to output errors, warnings, notices to the screen:
define( 'WP_DEBUG_LOG', true ); // To turn on logging
define( 'WP_DEBUG_DISPLAY', false ); // To prevent output of errors, warnings, notices to the screen (which I personally find SUPER annoying):
```

## Add Snippet.php code to your functions.php usually you would append to bottom. 

Once done you can now Call 

```php
write_log('Debug anything');
```

And you will see logs in your **_wp-content/debug.log_** file. 
