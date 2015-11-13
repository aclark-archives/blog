First Post
==========

.. post:: 2007/10/17

**I have decided to start a blog!**

|

.. image:: /images/balloons_clip_art_15536.jpg
    :align: center
    :class: img-thumbnail

|

Why? Because Plone allows me to do so. But also:

-  I have been reading a lot of Plone blogs lately and they have inspired me to write my own.
-  I want to interact with other Plonistas.
-  I want to get my web 2.0 on.

To that end, this post is about my `build tools`_ and how I love them. There are other ways to accomplish what I'm doing:

-  `Buildout`_
-  `Buildit`_
-  `Instance Manager`_

I used Buildout for the first time at the `Baarn UI Sprint 2007`_ and really liked it. I have also used Chris McDonough's Buildit. That may be where I end up and there are several more to choose from, but for now I enjoy typing:

::

    $ newzope test-site ProductA ProductB ProductC

and having a working instance a few seconds later with Product{A,B,C} installed. Of course this requires I have a working Zope already... and that I edit Zope's ``skel/etc/zope.conf``... but nothing is perfect and old habits die hard.

.. _Plone: http://plone.org/
.. _Plone blogs: http://planet.plone.org/
.. _build tools: http://svn.plone.org/svn/collective/newzope
.. _Buildout: http://www.buildout.org
.. _Buildit: http://agendaless.com/Members/chrism/software/buildit
.. _Instance Manager: https://plone.org/products/instance-manager
.. _Baarn UI Sprint 2007: https://plone.org/events/sprints/past-sprints/baarn-ui-sprint-2007
