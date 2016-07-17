===================================
reStructuredText Javascript Library
===================================

I love `reStructuredText`,
it provides readable syntax and let writer focus on content;
however, no one build the Javascript library for it.

It is necessary to build one; perhaps it is very difficult to implement,
performance issue, or something else.

The specification of `reStructuredText` is rich.
For implementation, some specification should be discussed and adjusted:

- User may not need fully support, the lib should be separated.
  For example, some directives

- Some directives not supported by Docutils may useful on web,
  they should be implemented

- Performance issue should be concerned

- Some features (eg: document title, bibliographic fields, ...) may be
  optional support, according to `reStructuredText` specification

- Require solutions (eg: basic editor) to help setting, setting sections,
  draw table, more default styles, and so on


.. image:: https://badges.gitter.im/apua/reStructuredText.svg
   :alt: Join the chat at https://gitter.im/apua/reStructuredText
   :target: https://gitter.im/apua/reStructuredText?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge