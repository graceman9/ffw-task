This file contains an explanation what was changed and why.

* sql query was changed because it was wrong
* $searchterm moved to the placeholder because of security
* table name was wrapped into brackets because table prefix can chage
* all nodes now are loading once because of performance profit
* nodes should be loaded in terms of extensibility. For example if we needed something else aside from 'title' or 'nid'.
* debug text should be outputted using devel or watchdog
* I use drupal standard functions l(), theme('item_list') because it's a best practices
* I use drupal t() because all strings need to be translated in case of multilingual site and it's also the best practices
* I use format_plural() because we need to provide most friendly text for the end-user
* drupal menu callback type was replaced with 'MENU_CALLBACK' value because  'menu suggested item' is redundant here
* indents were fixed according to drupal standards