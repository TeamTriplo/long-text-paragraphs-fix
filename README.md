Long Text Paragraphs Fix
======================

This simple module prevents unwanted empty long-text field items from being saved to the database for paragraphs.

Because of a [long-standing](https://github.com/backdrop/backdrop-issues/issues/5153), [stubborn Backdrop bug](https://github.com/backdrop/backdrop-issues/issues/5153), "long text" fields with unlimited cardinality keep adding empty items to the database every time a node with such a field is edited.

This module prevents that by removing empty items from long text fields paragraphs during a node presave hook.

<img width="500" height="479" alt="image" src="https://github.com/user-attachments/assets/88a02c29-0c7d-47a1-a976-df493d71a30d" />


Installation
------------
Install this module using the official Backdrop CMS instructions at https://backdropcms.org/guide/modules.
Once enabled check the node with paragraph and edit and then save, now the empty text fields issue will be gone also the previous listed empty fields will be removed from the node.


Current Maintainers
-------------------
- [Tim Erickson](https://github.com/stpaultim).
- [Sudipto Kumar Mitra (sudipto68)](https://github.com/sudipto68)

Credits
-------

- Sponsored by [Simplo](https://www.simplo.site)

License
-------

This project is GPL v2 software. 
See the LICENSE.txt file in this directory for complete text.


