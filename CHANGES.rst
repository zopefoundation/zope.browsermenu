=========
 Changes
=========

5.0 (unreleased)
================

- Add support for Python 3.10, 3.11.

- Drop support for Python 2.7, 3.5, 3.6.

- Add support for Python 3.7.

- Drop support for Python 3.4.


4.4 (2018-10-05)
================

- Add support for Python 3.7.


4.3.0 (2017-08-03)
==================

- Drop support for Python 3.3.

- Add support for PyPy3 3.5.

- Fix test compatibility with zope.component 4.4.0.

4.2.0 (2017-05-28)
==================

- Add support for Python 3.5 and 3.6.

- Drop support for Python 2.6 and 3.2.

- Drop support for 'setup.py test'.

4.1.1 (2015-06-05)
==================

- Add support for PyPy3 and Python 3.2.

4.1.0 (2014-12-24)
==================

- Add support for PyPy.  PyPy3 support is pending a release of fix for
  https://bitbucket.org/pypy/pypy/issue/1946).

- Add support for Python 3.4.

- Add support for testing on Travis.

4.1.0a1 (2013-02-22)
====================

- Add support for Python 3.3.

4.0.0 (2012-07-04)
==================

- Strip noise from context actions in doctests.

  Make output is now more meaningful, and hides irrelevant details.
  (forward-compatibility with ``zope.component`` 4.0.0).

- Replace deprecated ``zope.interface.implements`` usage with equivalent
  ``zope.interface.implementer`` decorator.

- Drop support for Python 2.4 and 2.5.

3.9.1 (2010-04-30)
==================

- Remove use of ``zope.testing.doctestunit`` in favor of stdlib's ``doctest``.

3.9.0 (2009-08-27)
==================

Initial release. This package was splitted off zope.app.publisher.
