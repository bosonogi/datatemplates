==============
 DBM Samples
==============

Creating Data File
==================

.. include:: make_dbm.py
   :literal:

Template File
=============

.. include:: _templates/dbm-sample.tmpl
   :literal:

Loading the Template
====================

.. code-block:: rst

   .. datatemplate:dbm::
      :source: sampledbm
      :template: dbm-sample.tmpl

Rendered Output
===============

.. datatemplate:dbm::
   :source: sampledbm
   :template: dbm-sample.tmpl
