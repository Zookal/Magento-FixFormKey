Zookal FixFormKey
===================

This module solves the issue where the form key will be cached in a block.

This modules creates a placeholder in the cached block and replaces later the placeholder
with the correct form key. The same replacement as with the session ID.

The modifications has been done in `Mage_Core_Block_Abstract` with its methods `_loadCache()`
and `_saveCache()`. The placeholder is generated in `_getFormKeyPlaceholder()`. Another solution is not possible.

## Compatible only with Magento CE >= 1.8 and EE >= 1.13


Install
-------

Please use modman or composer.org

License
-------
[OSL - Open Software Licence 3.0](http://opensource.org/licenses/osl-3.0.php)

Copyright
---------

Copyright (c) Zookal Pty Ltd, Sydney Australia

Author
------

[Cyrill Schumacher](https://github.com/SchumacherFM) - [My pgp public key](http://www.schumacher.fm/cyrill.asc)

Made in Sydney, Australia :-)
