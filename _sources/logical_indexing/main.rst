.. qnum::
   :prefix: Q
   :start: 1

.. raw:: html

   <link rel="stylesheet" href="../_static/common/css/matlab.css">
   <script src="../_static/common/js/exercises.bundle.js"></script>

===============================
Logical Operations and Indexing
===============================

.. admonition:: Chapter Files

  We'll be using several files throughout this chapter's exercises. It might be helpful to go ahead and download each of them now and move them to your current folder in MATLAB. (It's also a good idea to go ahead and create a new folder for this chapter and use that as your current folder, so that you don't clutter up whatever else you were working on.)

  .. list-table:: 
    :align: left
    :widths: auto

    * - :download:`rocks.csv <../_static/logical_indexing/rocks.csv>`

      - .. reveal:: rocks_csv_preview
          :showtitle: Preview
          :modal:
          :modaltitle: <code>rocks.csv</code>

          .. literalinclude:: ../_static/logical_indexing/rocks.csv
            :lines: 1-7
            :append: ...

      - Data file with rock samples and properties

    * - :download:`analyzeRocks.m <../_static/logical_indexing/analyzeRocks.m>`

      - .. reveal:: analyze_rocks_m_preview
          :showtitle: Preview
          :modal:
          :modaltitle: <code>analyzeRocks.m</code>

          .. literalinclude:: ../_static/logical_indexing/analyzeRocks.m
            :language: matlab

      - Starter script for loading/analyzing data from rocks.csv
    
  .. reveal:: logical_indexing_download_instructions
    :showtitle: Download Instructions
    :modal:
    :modaltitle: File Download Instructions for MATLAB
    
    .. include:: ../common/matlab_download_instructions.in.rst
      


^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Introduction and Relational Operators
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. section 1

We've seen that MATLAB supports *arithmetic* operations (e.g. :code:`+`, :code:`.*`, etc.), which allow us to write expressions that compute a *numeric* result. MATLAB (and most other programming languages!) also allow us to compare different values/variables to each other using *relational* operators that produce a *logical* (i.e. true or false) result. We'll introduce the basic idea and then give you a chance to practice.

.. youtube:: I13q-SPw9eo
  :divid: ch04_01_vid_relational_operators
  :height: 315
  :width: 560
  :align: center

|


--------------------------------------------
Exercise: Practice with Relational Operators
--------------------------------------------

.. include:: ex/relational_operations.in.rst

.. admonition:: Walkthrough

  .. reveal:: ch04_01_revealwt_relational_operations

   Please check the Piazza Q&A thread for links to the walkthrough videos.

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Using Logical Values and Logical Indexing
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. section 2

Let's take a look at some of the practical ways we can use logical results like the ones we get back from our relational operators.


.. youtube:: kgNw0oKcchg
  :divid: ch04_02_vid_logical_indexing
  :height: 315
  :width: 560
  :align: center

|

------------------------------
Exercise: Analyzing Some Rocks
------------------------------

.. figure:: img/rocks.png
   :width: 300
   :align: center
   :alt: rocks.png

   *a rock*

.. include:: ex/logical_indexing.in.rst

.. admonition:: Walkthrough

  .. reveal:: ch04_02_revealwt_relational_operations

   Please check the Piazza Q&A thread for links to the walkthrough videos.

^^^^^^^^^^^^^^^^^^^^^^^^^^
Logical Operators (and/or)
^^^^^^^^^^^^^^^^^^^^^^^^^^
.. section 3

Sometimes we want to ask complex questions about our data, for example "Which rocks have a high density *and* low metallicity?". We can do that in MATLAB.


.. youtube:: uzv0ZfLf_aM
  :divid: ch04_03_vid_logical_operators
  :height: 315
  :width: 560
  :align: center

|

----------------------------
Exercise: More Rock Analysis
----------------------------

.. figure:: img/rocks.png
   :width: 300
   :align: center
   :alt: rocks.png

   *hi it's me again*

.. include:: ex/logical_operators.in.rst

.. admonition:: Walkthrough

  .. reveal:: ch04_03_revealwt_logical_operators

   Please check the Piazza Q&A thread for links to the walkthrough videos.

^^^^^^^^^^^^^^^^^^^
Operator Precedence
^^^^^^^^^^^^^^^^^^^
.. section 4

Now that we have quite a few operators to work with, it makes sense to discuss how MATLAB determines order of operations according to the **precedence** of each operator.

.. youtube:: U8hXZPxLIsg
  :divid: ch04_04_vid_indexing_and_assignment
  :height: 315
  :width: 560
  :align: center

|

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Logical Indexing and Assignment
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. section 5

Let's take a look at some of the practical ways we can use logical results like the ones we get back from our relational operators.


.. youtube:: XGycZcWcU2I
  :divid: ch04_05_vid_indexing_and_assignment
  :height: 315
  :width: 560
  :align: center

|

---------------------------------
Exercise: Indexing and Assignment
---------------------------------

.. include:: ex/indexing_and_assignment.in.rst

.. admonition:: Walkthrough

  .. reveal:: ch04_03_revealwt_indexing_and_assignment

   Please check the Piazza Q&A thread for links to the walkthrough videos.