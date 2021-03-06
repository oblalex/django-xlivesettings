django-xlivesettings
====================

1. [Synopsis](#synopsis)
1. [Main differences](#main-differences)
1. [Installation](#installation)
1. [Usage](#usage)
1. [Dependensies](#dependensies)
1. [How does it look](#how-does-it-look)
  1. [Tabs](#tabs-from-test-project)
  1. [Localized strings](#localized-strings)

Synopsis
--------

django-xlivesettings is a fork of [django-livesettings] provided by [bkroeze]. Why X? Because it's eXtra.
Firstly it was forked on [Bitbucket](https://bitbucket.org/oblalex/django-livesettings/overview) and
then moved to GitHub.

Main differences
----------------

* Django 1.5 support.
* Little model definition fix.
* Code is more adapted for I18N.
* Settings groups are displayed via jQuery tabs.
* Localized strings support added.

Installation
------------

You can install either as [PyPi package](https://pypi.python.org/pypi/django-xlivesettings):

    pip install django-xlivesettings

or from your local sources:

    python setup.py install

Dependensies
------------

As this is a fork of another project, it inherits primary dependencies:

1. [django-keyedcache](https://pypi.python.org/pypi/django-keyedcache/)

No new dependencies were added.


Usage
-----

    # TODO:

How does it look
----------------

1. [Tabs](#tabs-from-test-project)
1. [Localized strings](#localized-strings)

#### Tabs ####
[Test-project] example:
![Tabs example](http://imageshack.us/a/img822/6467/snapshot42.png)
[Real project] example (flavoured with [Grappelli]):
![Tabs example with Grappelli](http://imageshack.us/a/img543/915/snapshot43.png)

#### Localized strings ####

You can view a kind of [presentation on Slideshare](http://www.slideshare.net/oblalex/localized-strings)
(strictly talking, it's a group of screenshots). It shows, that you can set localized string values for
settings keys. Target laguages are specified by [LANGUAGES](https://github.com/oblalex/django-xlivesettings/blob/53c43052b8ef0b242cb0c02ae32617717581f645/test-project/test_project/settings.py#L45)
in project's settings file.

[django-livesettings]:https://bitbucket.org/bkroeze/django-livesettings
[bkroeze]:https://bitbucket.org/bkroeze
[Test-project]:https://github.com/oblalex/django-xlivesettings/tree/master/test-project
[Real project]:http://goo.gl/2SWQ7
[Grappelli]:http://grappelliproject.com/
