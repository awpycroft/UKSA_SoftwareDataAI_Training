==============
Notebooks on C
==============

Attached here are some C notebookes as a refresher.  

C is not needed for the majority of the course and will not be needed for all delegates.  However, if you wish to deploy ML models to a small microcontroller such as an arduino then some C code will be needed. These basic notebooks will provide a code overview that can be used also as a reference. 

----------------
These notebooks:
----------------

Usually c programs are .c files compiled on the terminal. Scripting lanaguages are the ones often used with jupyter notebooks. However, it is possible to install a C kernel for your jupyter notebook and this gives a nice format for interacting with the language, especially when you might want to switch between C and python when prototyping code. The .yaml file provided for this course will install a C kernel for your own jupyter lab environment but you can also use `google colab <https://colab.research.google.com>`_ (with a small sysntax change where the program is saved and run in two steps) to run these codes. 

There are two of each notebook - one is labelled 'colab' - this can be run in colab (the c compilers are already installed and avalible there)

* 1 - a series of 'hello world' exmaples showing off basic information about the syntax. Remember with C - define everything and be careful with your puntuation!
* 2 - exploring basic datatypes
* 3 - using operators
* 4 - using loops and ocnditionals

If you are working on a work computer or another resource where installing packages is not easy we would reocmmend using google colab to view these notebooks. Please note that to complete the course you will not need to install python packages to your own machiene as computational resouces will be provided for you on our cluster.  You will only need your sign-in details to access this. 

To open these notebooks in google colab:

  1. click on the .ipynb file you wish to open - this will open another github page where you will see the notebook
  2. click the button on the top right hand corner of the opened notebook which says 'download raw file' - the icon for this looks like a down arrow over a line - make sure that you file is a .ipynb not an .html file
  3. open google colab here: `google colab <https://colab.research.google.com>`_ 
  4. on the 'open notebook' screen, click upload and find the downloaded file on your computer.
  5. To run cells in the notebook you can use the button 'runtime' or you can press shift+enter in each cell. 

---------------
Other resources
---------------

Other excellent and free learning resources for learning basic C are:
w3schools: https://www.w3schools.com/c/
geeksforgeeks: https://www.geeksforgeeks.org/c-programming-language/

If you wish to deploy code to an arduino you will want to install the arduino IDE: https://www.arduino.cc/en/software
And there are plenty of excellent tutorials here: https://www.arduino.cc/en/Tutorial/HomePage
