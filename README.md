Extrafield Views Integration
======================

The Extrafield Views Integration Module enables all drupal core extra fields in the system from type display as fields in views.

Installation 
------------

- Install this module using the official Backdrop CMS instructions at
  https://docs.backdropcms.org/documentation/extend-with-modules.
- The module itself needs no configuration, because the extra fields that you want to use need an callback key and a callback function. Every module can use hook_field_extra_fields() to register the extra fields.

Issues
------

Bugs and feature requests should be reported in [the Issue Queue](https://github.com/backdrop-contrib/extrafield_views_integration/issues).

Current Maintainers
-------------------

- [Eli Lisseck](https://github.com/elisseck).
- [Anthony Nemirovsky](https://github.com/anemirovsky).

Credits
-------

- Backdrop development supported by [USENIX](https://www.usenix.org/).
- Backdrop development supported by [Giant Rabbit](https://giantrabbit.com).
- Ported to Backdrop by [Lauren Blais](https://github.com/rlblais)
- Originally written for Drupal by [(dasRicardo)](https://www.drupal.org/u/dasricardo).

License 
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
