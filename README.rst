=====================================================
Collect Parts and Pieces to Start New Python Projects
=====================================================

.. default-role:: code
.. highlight:: bash

Readings
========

Inspired by `The Elements of Python Style <https://github.com/amontalenti/elements-of-python-style>`__.
See http://mbless.de/blog/2015/01/15/looking-for-wisdom-about-python.html#python-coding-style


Remember
========

::

   virtualenv venv
   source venv/bin/activate


   # http://nvie.com/posts/better-package-management/

   pip install -r            requirements.in
   pip install --requirement requirements.in

   pip freeze > requirements.txt


Development::

   pip install --upgrade --requirement requirements.in; pip freeze >requirements.txt

Production::

   pip install --requirement requirements..txt



Common Thirdparty Packages
==========================



docopt
------

Pythonic command line arguments parser, that will make you smile.

-  http://docopt.org
-  https://github.com/docopt/docopt


py.test
-------

unit tests
- http://pytest.org/latest/

python-dateutil
---------------

datetime parsing and calendars

-  https://labix.org/python-dateutil
-  https://dateutil.readthedocs.org


pytz
----

- World Timezone Definitions for Python http://pytz.sourceforge.net/


tldextract
----------

Accurately separate the TLD from the registered domain and subdomains of a URL, using the Public Suffix List.
Split URL into subdomain, domain and suffix.

-  https://github.com/john-kurkowski/tldextract


msgpack-python
--------------

It's like JSON. but fast and small.
MessagePack is an efficient binary serialization format. It lets you exchange
data among multiple languages like JSON. But it's faster and smaller. Small
integers are encoded into a single byte, and typical short strings require only
one extra byte in addition to the strings themselves.

-  http://msgpack.org/
-  https://github.com/msgpack/msgpack-python


six
---

-  https://pypi.python.org/pypi/six
-  https://pythonhosted.org/six/

futures
-------

-  https://code.google.com/p/pythonfutures/
-  https://docs.python.org/3/library/concurrent.futures.html
-  https://docs.python.org/dev/library/concurrent.futures.html
-  https://pypi.python.org/pypi/futures
-  https://pythonhosted.org/futures/

