# Drupal Panels to Drupal Panels migration
## migrate_panels

## Description

This is a framework based on the Migrate API and migrate_d2d to ease building migrations
from one Drupal site to another.


Support at this time is only for :

* Drupal 7 as the only destination
* Drupal 6 as the only source for initial release.

The core framework provided here is used by providing your own module, which
will register instances of the migrate_panels classes (or derivations of them).
See migrate_panels_example for one approach, where instances are registered when
the Drupal caches are cleared (note that registration updates previously-
registered classes with any argument changes).

## Road Map :

* Initial Release drupal 6 panels to drupal 7 panels.
* Addition of Drupal 7 Panels to Drupal 7 panels.
