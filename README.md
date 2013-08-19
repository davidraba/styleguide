EHP "HazDev" Styleguide
=======================

This project documents the coding style guide to be used by the Earthquake
Hazards Program (EHP) Hazards Development (HazDev) team. This project should be
considered a "living document" that adapts to best practices over time. If you
do not remain actively involved with the HazDev team over time, be sure to
re-check this style guide before starting any new development.

There is a vast set of existing code on the EHP web site. This guide is
relatively new compared to existing content. It is understood not all existing
content will conform to this guide. However every effort should be made to
adhere to this guide for new development.

Spacing
-------

We use "smart tabs"  with a two-column tab stop. This means use hard-tab
characters for indentation while using space characters for alignment.

Column Width
------------

We use an 80 column max width on our documents. This rule should be followed as
often as is feasible without breaking language syntax rules. If a single line of
code is wrapped to two or more lines in the file, the subsequent line(s) should
be indented by two tabs offset from the starting line of code.

Whitespace
----------

All trailing white space should be removed. A final newline should be inserted
at the end of every file. A single line feed character is used for new lines.

Approach
--------

We use a [mobile first][1], approach to [progressively enhance][2] web
applications in a [responsive][3] manner.

Support
-------

By policy we explicitly support the current browser version plus one version
previous for major vendors. We make no effort to directly inhibit older browsers
from functioning properly, however resources limit the extent to which we can
test products and therefor testing is skipped on unsupported browsers/devices.

Language Specific Guides
------------------------

 + [HTML(5)](html/)
 + [Javascript](javascript/)
 + [CSS](css/)
 + [PHP](php/)


[1]: http://www.lukew.com/ff/entry.asp?933
[2]: http://en.wikipedia.org/wiki/Progressive_enhancement 
[3]: http://en.wikipedia.org/wiki/Responsive_web_design
