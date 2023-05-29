Intro
=====

**The Sinara ML Definitive Guide** is a guide to systematic development of ML models using the Sinara Framework. This guide is about ML pipelines (ML system) development not about using specialized Data Science libraries to train models or mathematics. Sinara Framework allows the Data Scientist to focus on Data Science tasks by minimize the efforts associated with engineering and other dev and ops tasks.

The problem of data science in non-IT companies 
==================================================================================
Why are so many companies starting to develop AI experiencing serious difficulties? If we ask such a question to the developers of AI systems, then we will get a lot of different answers, but the story as it is seen from the side of the Data Scientist is the same.

Let's imagine a large non-IT company that started to develop AI and in which data scientists appeared. Adam released the first model. Passed the "weights" and a few py files to the prod. 

Three months have passed and Ivan is given the task to retrain the model on the updated data. Ivan comes to Adam and asks to see how Adam trained the code.Adam finds his code, although he is not sure if this is the code he trained the model on. He tries to run it, but he does not remember how he installed the environment and in what order he launched the files. He finds some data, but he is not sure what it is. He is trying to run the code, but is not very successful. The code is too complex to figure out what went wrong on the fly. He makes a correction in one place and then everything goes wrong in another place.

As a result, Ivan is left with a broken code, some kind of data, a hint of some kind of ritual procedure that will revive the dead man. Ivan tries to restore the ritual knowledge, at which time Adam leaves the company. Then after a long and agonizing attempt Ivan comes to the conclusion that the code is wrong, the data are wrong, some of it is lost and, in general, it is easier to do everything over again.

Management is upset, why does it have to do all of the work from the beginning because of a minor change? Why is everything so long and expensive in ML?

The answer lies in the field of engineering and organization of development and operation of ML systems. With the seeming similarity of approaches and tools with software dev, ML development and operation has many of its own ML specifics, and in addition to specialized tools and approaches, also requires a rethinking of traditional dev practices. Moreover, the use of AI in non-IT companies leads to additional challenges: we often have to solve AI tasks with fewer resources and competencies compared to IT companies. 


.. note::

   This project is under active development.

.. _installation:

Installation
------------

To use Lumache, first install it using pip:

.. code-block:: console

   (.venv) $ pip install lumache

Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

