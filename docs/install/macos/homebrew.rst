.. _package-managed-reference-macos:


{{ apple_icon }} --- Homebrew installation
============================================

.. button-link:: ../windows/manual.html
   :align: right
   :color: primary
   

    Press here for Windows {{ windows_icon }}



Step 1: Install Homebrew 
--------------------------


.. card:: 

    #.
        Go to `this website <https://brew.sh>`_ and follow the instructions.
        
    #.  
        The Homebrew website will ask you to open a terminal.
        This can be done by pressing :kbd:`Command+Space` at the same time.
        Then search for :menuselection:`Terminal` and press :kbd:`Enter`.
        Do *not* close the terminal once the installation script has finished.

        .. image:: ../images/MacOS-spotlight-terminal.png
            :width: 100%
            :align: center

        .. image:: /images/install/macos-package-managed-homebrew.png
            :width: 400
            :align: center

    #.
        
        Add Homebrew to the **PATH** by copying, pasting and running the code that Homebrew displays in the terminal (look at the picture for guidance). 
        Press :kbd:`Enter` once you have pasted the code. The code should look similar to the following image, 
        but might differ a little for different {{ macos }} versions.

        .. image:: /images/install/macos-package-managed-homebrew-terminal-instructions.png
            :width: 400
            :align: center



.. _step2-homebrew-reference:

Step 2: Install Miniconda and Python
-------------------------------------

.. card::

    #. 
        Close the previously used terminal, and open up a new terminal (:kbd:`Command+Space`).

    #.
        Paste the following code in the terminal and press :kbd:`Enter`.

        .. code-block:: bash

            brew install --cask miniconda

    #.
        Run the following command in the terminal by pasting and pressing enter:

        .. code-block:: bash

            conda install python=3.11 -y ; conda install -c conda-forge dtumathtools uncertainties -y
            
    .. tip::
        You can copy and paste all code in the gray code blocks below by hovering your mouse over the block and pressing the icon in the top right.
        
    

Step 3: Install Visual Studio Code 
-----------------------------------

.. card::
    
    Install Visual Studio Code by pasting the following in your terminal and pressing :kbd:`Enter`.

    .. code-block:: bash

        brew install --cask visual-studio-code


Step 4: Install extensions for Visual Studio Code
-------------------------------------------------

.. |extensions| image:: /images/install/extensions.png
    :height: 25px

.. card:: 

    #. 
        Open Visual Studio Code and select the Extensions |extensions| tab on the left.

         .. image:: ../images/VSC-extensions.png
            :width: 400
            :align: center
    
    #.  
        Search for Python, and download the extension. Make sure that it is from Microsoft. 

        .. image:: /images/install/macos-package-managed-python.png
            :width: 200
            :align: center

    #. 
        Hereafter search for Jupyter, and download that extension as well. This also needs to be from Microsoft.
        
        .. image:: /images/install/macos-package-managed-jupyter.png
            :width: 200
            :align: center



.. tip::
    When you have finished the guide, we **strongly recommend** checking out the :ref:`Python Essentials <essentials-reference>` to prepare you for coding.


.. include:: verify.rst
