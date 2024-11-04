Emogifier
======================

Converts stylesheets to inline style rules for better compatibility with email and mobile device viewers. Uses the now included Emogrifier library.

Installation
------------

- Ensure that the PHP Document Object Model extension is available. Emogrifier requires the dom extension and will not work without it.
- Emogrifier library has been placed within the module in emogrifier/libraries/emogrifier/Classes/emogrifier.php 
- Install this module using the official Backdrop CMS instructions at
  https://docs.backdropcms.org/documentation/extend-with-modules.
- Visit admin/config/content/formats or click on Configuration >> Content Authoring >> Text Format and Filters to set up a new input format, or add Emogrifier filtering to an existing format. 
- Within the format, you'll see the ability to configure Emogrifier under the filter list. 

Issues
------

Bugs and feature requests should be reported in [the Issue Queue](https://github.com/backdrop-contrib/emogrifier/issues).

Current Maintainers
-------------------

- [Eli Lisseck](https://github.com/elisseck).
- [Anthony Nemirovsky](https://github.com/anemirovsky).

Credits
-------

- Backdrop development supported by [USENIX](https://www.usenix.org/).
- Backdrop development supported by [Giant Rabbit](https://giantrabbit.com).
- Ported to Backdrop by [Lauren Blais](https://github.com/rlblais)
- Originally written for Drupal and co-maintained by [Robert Vincent (pillarsdotnet)](https://www.drupal.org/u/pillarsdotnet), [monstrfolk](https://www.drupal.org/u/monstrfolk), [Niels de Feyter (ndf)](https://www.drupal.org/u/ndf)

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
