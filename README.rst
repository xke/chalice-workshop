====================
AWS Chalice Workshop
====================

This repository contains code for the AWS Chalice workshop


Repo Layout
===========

* ``docs/`` - The writeup for the workshop.  Includes the step-by-step guide
  for each part of the workshop.  This is a sphinx project and can be used to
  generate both html as well as a pdf of the guide.
* ``code/`` - This is broken down into two sections.  The first section is
  creating the sample app.  The second second seciton is for deploying this
  application using AWS CodePipeline.
* ``slides/`` - This is the slide deck used to run the workshop.  It's broken
  down into two slide decks, one for each phase.  The main (combined) slide
  deck is ``ChaliceDay.key``.


Building the Docs
=================

Install requirements::

    $ pip install requirements.txt


Build html docs::

    $ make html
