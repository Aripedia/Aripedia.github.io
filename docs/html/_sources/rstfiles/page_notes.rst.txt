===================================
Notes related to this page
===================================

To-do tasks
-----------------------------------

* Week 2:
   #. Learn to use substitions and hyperlink text.

      .. code-block:: rest
      
         .. _selenium-mineral:

         :ref:`selenium <selenium-mineral>`

         .. _protein-label:

         :ref:`protein-label`


   #. Learn to use csv tables - https://sublime-and-sphinx-guide.readthedocs.io/en/latest/tables.html

      .. code-block:: rest
      
         .. csv-table:: Table Title
            :file: moussaka_nutrition.csv
            :header-rows: 1


   #. Together - add program of what to study (for i.e. nutrition)
   #. Use Greenshot to take/add images to pages

* Week 3:
   #. Add new sub-branch to page structure, by adding a new toctree directive (as in index.rst and recipes.rst)
   #. Learn to use GitHub to backup and restore page versions
   #. Learn to edit conf.py to change page themes

* Week 4:
   #. Learn to use (some tools) to do mass find/replace operations

.. todolist::


Completed tasks
----------------------------------

* Week 1:
   #.  Use ``.. image::`` directive to insert images into pages.  Use ``:alt:`` option to add metadata to all images (brief description of image). http://docutils.sourceforge.net/docs/ref/rst/directives.html#images
   #.  Use ``.. todo::`` directive to remember parts to add later.  http://www.sphinx-doc.org/en/master/usage/extensions/todo.html
   #.  Use ``.. toctree::`` and ``:maxdepth:``, located in index.rst, to change Table Of Contents visible depth. Change ToC caption.
   #.  Add content outside of recipes (nutrition, chemistry, etc)