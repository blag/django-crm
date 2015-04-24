django-crm
==========

django-crm is an open source Django Customer Relationship Management (CRM) pluggable app.

This project was originally extracted from [minibooks](https://secure.caktusgroup.com/projects/minibooks/), the open source Django CRM and bookkeeping package.

Quick Start
===========

While it's just a Django app, the easiest way to get started with django-crm is to clone this project and switch to the `sample_project` directory, then configure your database settings and SECRET_KEY in settings.py, run `./manage.py syncdb`, and `./manage.py runserver`.

Dependencies
============

django-crm depends on the following pluggable apps:

 * http://code.google.com/p/django-contactinfo/ django-contactinfo
 * http://code.google.com/p/django-countries/ django-countries
 * http://code.google.com/p/django-crumbs/ django-crumbs
 * http://code.google.com/p/django-notify/ django-notify
 * http://code.google.com/p/django-ajax-selects/ django-ajax-selects
 * http://code.google.com/p/django-pagination/ django-pagination

Features
========

Users in an optional "Contact Notifications" Group will receive an email including a diff of the changes made.

Sponsors
========

Development sponsored by [Caktus Consulting Group, LLC](http://www.caktusgroup.com/services)
