FE_VARIABLE
===========

A Drupal 7 module to make Drupal variables featurable.
More on why and how to use Drupal Features module: [here](https://fosswiki.liip.ch/display/DRUPAL/Drupal+7+using+the+features+module).

If you're interested in exporting i18n variables, have a look at the [fe_variable_i18n module](https://github.com/liip/fe_variable_i18n).

Dependencies
------------------
 * [Features module](http://drupal.org/project/features)

Why not use Strongarm?
------------------

We experienced quite a few problems with Strongarm, especially when combined with i18n. Strongarm is way more powerful and tries to be much smarter than this module in that it creates strongarm variables to override core variables. This module just lets you export and import variables.
