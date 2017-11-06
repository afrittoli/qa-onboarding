. display in 68x24

.. transition:: dissolve
   :duration: 0.4

QA Onboarding
=============
.. hidetitle::

QA Onboarding - Sydney, Nov 6th 2017

About this presentation
=======================

* https://github.com/afrittoli/qa-onboarding
* presentty

About us
========

* Ghanshyam Mann, gmann
* Masayuki Igawa, masayukig
* Oomichi Ken'ichi, oomichi
* Andrea Frittoli, andreaf

Agenda
======

* Background
* Things we work on
* QA Projects
* How to contribute
* Questions

Background
==========

* Gating testing
* Gerrit, zuul & other infra stuff
* https://docs.openstack.org/infra/system-config/

Things we don't work on
=======================

* Big T^H^H^H^H Large project ecosystem
* Community driven approach to QA
* Each project team owns their QA

Other things we don't do
========================

* Manual testing :]

Things we do
============

* Serve the OpenStack community
* Drive best practices
* Test Frameworks
* Test Environment

Other things we do
==================

* Help keep the gate running
* Support Interoperability
* https://governance.openstack.org/tc/reference/projects/quality-assurance.html 

Dev & Test environment
======================

* Devstack
* Devstack-tools (python)
* Devstack plugin interface

Test Frameworks
===============

* Tempest integration testing
* Tempest plugin interface
* Tempest CLI testing
* Grenade upgrade testing
* Grenade plugin interface
* Patrole policy testing

Syntax Checks
=============

* Hacking
* eslint-config-openstack
* bashate

Test runners
============

* stestr
* os-testr

Test results
============

* openstack-health
* stackviz
* coverage2sql

How to contribute
=================

* Developer workflow

  * https://docs.openstack.org/upstream-training/upstream-training-content.html

* Fix a bug

  * Use QA tools, and then you can find documents or some other issues

* Queens Cycle Items:

  * https://etherpad.openstack.org/p/qa-queens-priorities  

Questions
=========

* What would you like to talk about?

* Some ideas:
* Why plugins
* Writing new tests
* Tempest stable interfaces
* What is going on

Contacts
=======

* openstack-dev ML, tag [QA] in subject
* #openstack-qa in IRC, office hours, meetings
