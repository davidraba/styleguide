Cascading Style Sheets (CSS)
============================

CSS selectors shall be placed on a single line per selector. If multiple
selectors are used for a single set of styles, each selector shall be placed on
its own line. Multiple selectors shall be separated with a comma.

The opening curly brace for a block of styles shall be on the same line as the
last selector for that block of styles. The closing curly brace for a block of
styles shall be left-aligned (using indentation) with the selectors for the
styles. Styles within a block shall be indented by a single tab character.

Media Queries
-------------

Media queries shall be used in-line with the CSS rather than on the ``<link>``
tag itself. Base styles shall be targeted for a mobile audience and media
queries (via min-width or similar) shall be applied on top of base styles to
enhance the page.

The opening curly brace for a media query block shall be on the same line as the
media query definition. Selectors within a media query shall be indented by one
tab character. The closing curly brace for a media query shall be left-aligned
(using indentation) with the media query definition.

Convention
----------

Avoid:
 + ``!important``
 + ID selectors
 + unscoped selectors

Prefer:
 + class selectors
 + direct descendant selectors

Extensions
----------

SCSS and Compass libraries may be used at the developer's discretion. Do not use
LESS. Web applications developed in the "hazdev-webapp" framework provide this
support inherently; other development efforts must be manually customized to
work with these extensions.
