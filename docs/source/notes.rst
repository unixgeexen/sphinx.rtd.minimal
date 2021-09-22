Starter Sphinx/RestructuredText Notes
=====================================

Introduction
************
This site provides a starter set for a sphinx/RST site.  It demonstrates various features providing code examples to be copied into your own site.  The Introduction chapter is a summary of `Sphinx RTD Tutorial <https://sphinx-rtd-tutorial.readthedocs.io/en/latest/sphinx-quickstart.html>`_ providing commands and other actions required to set up a site from scratch running through github into Read The Documents.

Todo
****
Tasks required to bring this starter site to a standard to be shared

* Summarise introduction notes from xxxxx to provide a short summary and link to the original
* Document features used within this site
* Clean make html errors
* Create a multi-directory structure which requires minimal configuration
    * index.rst
        * one for each subdirectory
        * includes index.rst in all it's subdirectories
        * includes all \*.rst files in it's own directory
        * check if there's automatic references for my directory structure - include in index.rst
    * Steps for adding a subdirectory
        * mkdir NewDirectory
        * cp GenericIndex.rst NewDirectory/index.rst - update header
        * create required \*.rst files in NewDirectory

