Twig Extensions Repository
==========================

This repository hosts Twig Extensions that do not belong to the core but can
be nonetheless interesting to share with other developers.

Fork this repository, add your extension, and request a pull.

More Information
----------------

Read the `documentation`_ for more information.

.. _documentation: http://twig-extensions.readthedocs.io/

Changes from upstream
---------------------

This is a long term fork from twigphp/Twig-extensions, because some change that is important to me won't be merged.

* `\Twig_Extensions_Node_Trans`: Replaces consecutive whitespace and line breaks with a single space. This is similar
  to the default HTML text node behavior and allows you to have normal text as translation messages, which may span
  multiple lines. This change was not merged upstream, because it may break existing translation messages. It's useful
  if you are accustomed to gettext style translation messages and want to have HTML text node behavior.