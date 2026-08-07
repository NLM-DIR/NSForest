Installation
============

To install NS-Forest via Github: 

.. code-block:: console

   git clone https://github.com/NLM-DIR/NSForest.git
   cd NSForest
   
Now we create the environment with all the dependencies required to run
NS-Forest, including the ability to run a Jupyter Lab notebook version of
the tutorial. This has been verified on Linux (Python 3.14.3) and on
macOS (Apple Silicon, Sonoma 14.6, Xcode Command Line Tools installed).

Once the environment is created, activate it and install the package:

.. code-block:: console

   conda env create -f nsForest_env.yml
   conda activate nsForest_env
   pip install .


There are 2 ways to run NS-Forest: Jupyter Notebook and command line.

Jupyter Notebook: ``docs/source/tutorial_nsforesting.ipynb``

.. code-block:: python
   
   import nsforest as ns
   from nsforest import utils

Command Line: ``nsforest/__main__.py``

.. code-block:: console

   python3 -m nsforest

