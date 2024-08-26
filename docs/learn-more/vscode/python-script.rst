Python files (.py)
===================

.. dropdown:: Video Tutorial
   :color: muted
   :open:

   .. raw:: html 
      
         <iframe src="https://panopto.dtu.dk/Panopto/Pages/Embed.aspx?id=7c0cdab0-d90e-4858-bb3e-b1d5009e11f8" height="405" width=100% style="border: 1px solid #464646;" allowfullscreen allow="autoplay"></iframe>



A ``.py`` file is a text file that contains Python code. 
It's the standard file format used for writing and executing Python programs. 
When you write Python code in a ``.py`` file, you can run the file to execute the code it contains,
and it can be opened and edited in any text editor or integrated development environment (IDE) like VS Code or IDLE.

In this tutorial you will learn how to do all of these using Visual Studio Code:

.. contents::
   :local:
   :depth: 2


Opening a Folder
------------------

Opening a folder in VS Code allows you to manage all your project files in one place.

.. card::

   .. tab-set::
      :sync-group: os

      .. tab-item:: {{ windows }}
         :sync: windows

         1. Press the :menuselection:`File` button in the top left corner of VS Code.
         2. Select :menuselection:`Open Folder...` from the dropdown menu.

            .. image:: ../images/VSC-openfolder.png
               :width: 80%
               :align: center
               :alt: Save File in VS Code

         3. Browse to the folder you want to open and select it.


      .. tab-item:: {{ macos }}
         :sync: mac

         1. Press the :menuselection:`File` button in the top left corner of your screen.
         2. Select :menuselection:`Open Folder...` from the dropdown menu.

            .. image:: ../images/openFolderMac.png
               :width: 80%
               :align: center
               :alt: Open Folder in VS Code

         3. Browse to the folder you want to open and select it.    


Creating a Python-file
-----------------------

You can create a Python file using VS code. This is useful if you are writing code that you will need again. 

.. card::      

   .. tab-set::
      :sync-group: os

      .. tab-item:: {{ windows }}
         :sync: windows

         Press the :menuselection:`File` button in the top left corner of VS Code. Select :menuselection:`New File --> Python File` from the menu that drops down. 

         .. image:: ../images/VScode_windows1.png
            :width: 80%
            :align: center
            :alt: IDLE Shell


      .. tab-item:: {{ macos }} 
         :sync: mac

         Press the :menuselection:`File` button in the top left corner of your screen. Select :menuselection:`New File --> Python File` from the menu that drops down. 
         You may need to hover your mouse around the top of the screen for the menu bar to appear.

         .. image:: ../images/VScode_mac1.png
            :width: 80%
            :align: center
            :alt: IDLE Shell

                       

Saving a File
--------------

Saving a file in VS Code ensures that your work is not lost and can be accessed later.

.. card::
    
   .. tab-set::
      :sync-group: os

      .. tab-item:: {{ windows }}
         :sync: windows

         1. Press the :menuselection:`File` button in the top left corner of VS Code.
         2. Select :menuselection:`Save` or :menuselection:`Save As...` from the dropdown menu.

            .. image:: ../images/VScode_windows_save_file.png
               :width: 80%
               :align: center
               :alt: Save File in VS Code

         3. Please choose a location and name for your file, then save it.

         Note, you can save a file by pressing :kbd:`Ctrl+S`.

      .. tab-item:: {{ macos }}
         :sync: mac

         1. Press the :menuselection:`File` button in the top left corner of your screen.
         2. Select :menuselection:`Save` or :menuselection:`Save As...` from the dropdown menu.
         3. Please choose a location and name for your file, then save it.

            .. image:: ../images/saveFileMac.png
               :width: 80%
               :align: center
               :alt: Save File in VS Code

         Note, you can save a file by pressing :kbd:`Command+S`.

   .. tip::

      You can enable auto save by pressing the :menuselection:`File` button in the top left corner of VS Code and then selecting :menuselection:`Auto Save`.


Opening a File
---------------------------

Opening a file in VS Code allows you to edit and run your code directly within the editor.

.. card::

   .. tab-set::
      :sync-group: os

      .. tab-item:: {{ windows }}
         :sync: windows

         1. Press the :menuselection:`File` button in the top left corner of VS Code.
         2. Select :menuselection:`Open...` from the dropdown menu.

            .. image:: ../images/VSC-openfile.png
               :width: 450
               :align: center
               :alt: Save File in VS Code

         3. Browse to the file you want to open and select it.
            

      .. tab-item:: {{ macos }}
         :sync: mac

         1. Press the ":menuselection:`File` button in the top left corner of your screen.
         2. Select ":menuselection:`Open...` from the dropdown menu.

            .. image:: ../images/openFileMac.png
               :width: 450
               :align: center
               :alt: Open File in VS Code

         3. Browse to the file you want to open and select it.    

   .. tip::

      You can open a file by dragging and dropping it directly into the VS Code window.


Selecting the right interpreter
-------------------------------

Once you have created a Python file, select your interpreter.
In short, the interpreter is the version of Python that you use to execute your code.

.. card::

   .. tab-set::
    
      .. tab-item:: {{ windows }} 
         :sync: windows

         1. Press :kbd:`Ctrl+Shift+P`
         2. Type *Python: Select Interpreter* and press :kbd:`Enter` once this shows up under the options 

            .. image:: ../images/VScode_windows2.png
               :width: 450
               :align: center
               :alt: IDLE Shell

         3. Choose the option similar to ``Python {{python_version_recommended}}.X ('base')``.
            Your PC may have a different version of Python.
            
            .. image:: ../images/VScode_windows3.png
               :width: 450
               :align: center
               :alt: IDLE Shell


         .. tip::

            In VS Code, pressing :kbd:`Ctrl+Shift+P` brings down a search bar where you can search for help with anything.

      .. tab-item:: {{ macos }}
         :sync: mac

         1. Press :kbd:`Ctrl+Shift+P`
         2. type *Python: Select Interpreter* and press :kbd:`Enter` once this shows up under the options 

            .. image:: ../images/VScode_mac2.png
               :width: 450
               :align: center
               :alt: IDLE Shell
                        
         3. Choose the option similar to ``Python {{python_version_recommended}}.5 ('base')``. You may have a different version of Python on your own PC.

            .. image:: ../images/VScode_mac3.png
               :width: 450
               :align: center
               :alt: IDLE Shell

         .. tip::

            In VS Code, pressing :kbd:`Ctrl+Shift+P` brings down a search bar where you can search for help with anything.
            

.. todo::
   Fill this section called Run a Python File accordingly once the video includes this info. Sotero should be done with the video during week 19/8 - 23/8



.. Run a Python File - Needs to be redone according to video
.. ----------------------------------------------------------------

.. Once you've written your Python code, you can easily run it in VS Code.

.. .. tip

..                 Once you've selected the right interpreter you can run all the code in your python file by clicking the icon shaped like a play button in the top right of VS Code.
    

..   .. tab-set::
..      :sync-group: os

..         .. tab-item:: {{ windows }}
..               :sync: windows

..             1. Open the Python file you want to run.
..             2. Press :kbd:`Ctrl+Shift+P`.
..             3. Type *Run Python File in Terminal* and select it from the options.
..             4. Alternatively, you can click the play button icon in the top right corner of the VS Code window.

..             .. image:: ../images/VScode_windows_run_python.png
..                 :width: 450
..                 :align: center
..                 :alt: Run Python File in VS Code

..         .. tab-item:: {{ macos }}
..               :sync: mac

..             1. Open the Python file you want to run.
..             2. Press :kbd:`Command+Shift+P`.
..             3. Type *Run Python File in Terminal* and select it from the options.
..             4. Alternatively, you can click the play button icon in the top right corner of the VS Code window.

..             .. image:: ../images/VScode_mac_run_python.png
..                 :width: 450
..                 :align: center
..                 :alt: Run Python File in VS Code



.. todo::
   Fill this section called Difference between... accordingly once the video includes this info. Sotero should be done with the video during week 19/8 - 23/8

.. Difference between Terminal and Python shell in VS Code - Needs to be redone according to video
.. ------------------------------------------------------------------------------------------------------------------------

.. You can start a terminal from VS code, which works just like in the terminal app. 

.. .. card      
    
..     .. tab-set
..      :sync-group: os

..        .. tab-item:: {{ windows }}
..         :sync: windows

..            Press the three dots in the top menu bar. They are next to the :menuselection:`View` and :menuselection:`Go` options.
..            Move your mouse to :menuselection:`Terminal` and click :menuselection:`New Terminal`

..            .. image:: ../images/VScode_windows4.png
..                :width: 450
..                :align: center
..                :alt: IDLE Shell

..        .. tab-item:: {{ macos }}
..          :sync: mac

..            Move your mouse to the top of the screen. Select :menuselection:`Terminal --> New Terminal`

..            .. image:: ../images/VScode_mac4.png
..                :width: 450
..                :align: center
..                :alt: IDLE Shell
.. tip
..     You can have multiple terminals open at once. 
..     You can delete a terminal by hovering your mouse over it's name (bottom right) and pressing the icon shaped like a trash can



