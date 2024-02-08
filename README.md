Extrafield Views Integration
======================

The Extrafield Views Integration Module enables all drupal core extra fields in the system from type display as fields in views.



Requirements 
------------

This module requires that the following modules are also enabled:

 * [Views (in Backdrop Core](https://docs.backdropcms.org/api/backdrop/core%21modules%21views%21views.module/1)
 * [Entity API (in Backdrop Core)](https://docs.backdropcms.org/api/backdrop/core%21modules%21entity%21entity.module/1)

Installation 
------------

- Install this module using the official Backdrop CMS instructions at
  https://docs.backdropcms.org/documentation/extend-with-modules.

- The module itself needs no configuration, because the extra fields that you want to use need an callback key and a callback function. Every module can use hook_field_extra_fields() to register the extra fields.


Documentation 
-------------

Additional documentation is located in [the Wiki](https://github.com/backdrop-contrib/extrafield_views_integration/wiki/Documentation).

Issues
------

Bugs and feature requests should be reported in [the Issue Queue](https://github.com/backdrop-contrib/extrafield_views_integration/issues).

Current Maintainers
-------------------

- [Giant Rabbit](https://github.com/giant-rabbit).

- Seeking additional maintainers.


Credits
-------

- Ported to Backdrop CMS by [Giant Rabbit](https://github.com/giant-rabbit).
- Porting to Backdrop CMS development sponsored by [USENIX](https://www.usenix.org/).
- Originally written for Drupal by [(dasRicardo)](https://www.drupal.org/u/dasricardo).
- Based on [Extrafield Views Integration](https://www.drupal.org/project/extrafield_views_integration).

License 
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.


