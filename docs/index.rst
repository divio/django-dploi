.. django-dploi documentation master file, created by
   sphinx-quickstart on Mon Nov  8 12:41:59 2010.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to django-dploi's documentation!
========================================

Other projects solving similar problems:


* https://github.com/bretth/woven
* https://github.com/robmadole/django-sunset


Defining a deployment
---------------------

Every deployment consists of an Deployment Class that is registered on the
deployment manager.

The Deployment has an unique name and knows in what directory on which hosts it is 
(or should be) deployed to. It also has Database settings and holds other "secret"
stuff like API-keys and passwords. Some settings will be re-usable as django
settings.




Contents:

.. toctree::
   :maxdepth: 2

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

