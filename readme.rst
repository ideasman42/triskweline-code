
****************
Triskweline-Code
****************

This is a modified version of the Triskweline bitmap font,
from `netalive.org <http://www.netalive.org/tinkering/triskweline>`__ (2009-03-16).
with minor changes for improved readability with code.


Screenshot
==========

.. figure:: https://cloud.githubusercontent.com/assets/1869379/12693179/73618e78-c757-11e5-9799-31574a4c4b5a.png


Changes
=======

- Added bold version.
- Gap added between underscore characters.
- Star and tilde and equals characters (``*``, ``~``, ``=``):
  lowered to vertically align with plus, hyphen and other operators.
- Punctuation characters (``.``, ``,``, ``;``, ``:``, ``\```):
  Avoid single pixel dots, for increased visibility.
- Accentuate loop on lowercase ``l`` to distinguish it from ``ij1|`` characters.
- Moved from ``ISO8859`` encoding to unicode ``ISO10646``.


Added Characters
================

These symbols are included to display common symbols used to replace
symbols used in programming languages using Vim's *conceal*
or Emacs' pretty-symbols feature.

Misc Symbols:

- ``U8226``    (•) Bullet/dot character.
- ``U8228``    (․) leader (dot).
- ``U8229``    (‥) leader (two dots).
- ``U8230``    (…) ellipsis character.
- ``U9474``    (│) vertical separator.
- ``U9475``    (┃) vertical separator (wide).

Left and right single and double quotes:

- ``U8220``    (“)
- ``U8221``    (”)
- ``U8216``    (‘)
- ``U8217``    (’)

Math/Logic Symbols:

- ``U995``     (λ) lower-case lambda.
- ``U402``     (ƒ) lower-case italic 'f'.
- ``U120333``  (𝘍) upper-case italic 'F'.

- ``U8594``    (→) right arrow.
- ``U8592``    (←) left arrow.
- ``U8658``    (⇒) right double arrow.
- ``U8656``    (⇐) left double arrow.
- ``U8800``    (≠) not equal to.
- ``U8801``    (≡) equivalent to.
- ``U8802``    (≢) not equivalent to.
- ``U8803``    (≣) strict equivalent to.
- ``U8804``    (≤) less than or equal to.
- ``U8805``    (≥) greater than or equal to.
- ``U10869``   (⩵) two consecutive equals signs.
