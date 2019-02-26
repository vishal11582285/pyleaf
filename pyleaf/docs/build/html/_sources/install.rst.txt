============
Installation
============

Download the source package from GitHub repository::

    https://github.com/vishal11582285/pyleaf.git

Once downloaded, you should be able to locate the below files and directories::

    all_photos : All raw images that can be used for processing
    limited_images: Set of limited chosen images for testing purpose
    saved_images: This will be the default save directory. <Do not change name of this folder>
    test_images: Contains all the test images for training the CNN model for classification task.

    model.h5, model.json: Already trained model. Ready for immediate use.


.. code-block:: bash

    Locate the setup.py file
    In command prompt, type:
    python setup.py build
    python setup.py install

You should now be able to see the package pyleaf in site_packages of your Python interpreter.

============
Usage
============
Open up the Python interpreter::

    >>import pyleaf
    should open up the pyleaf GUI for use.

============
GUI Features
============
On the GUI Application, you will find various options to get you started right away::

    Batch Process:
    Select default image folder from File->Select Default Image Path
    Then select Tools->Batch Process to run leaf area analysis on all images in chosen folder.

    Single Image Analysis:
    Use Select Images button to select one or more image(s) and click Process Images to view the results.

    Use the navigation page under original window preview to load all selected images.

    Reset Workspace button clears the workspace for a fresh start.

    Tools->Retrain Model to re-train CNN clasification model based on updated training images in test_images/ folder.

    Tools->View Recent Results to open up a window and view the image and their calculated areas in tabular format.
