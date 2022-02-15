.. _first_setup:

How to run first_setup.sh
#########################

This guide will help you learn how to run the first_setup.sh script when deploying fresh securebooks

-------------
Prerequisites
-------------

To accomplish this process you will need:

* WP Securebook
* Default jadmin Password
* New Student's Name and Password
* New jadmin Password
* Current Date and Time

.. note::

    Double Check all information entered during this script as it should only be run once.

To complete the First Setup process, follow these steps:

1. Power On the Securebook
2. Login to the jadmin account using the default password
3. Open the Terminal Application (Click Icon on the Desktop or Type 'Terminal' in the Searchbar)

.. image:: ../_resources/01_FSetupTerminal-1.png

4. Run the following command:

.. code-block:: bash
    :linenos:
    
    sudo bash first_setup.sh
    
5. Follow the On-Screen prompts

* Enter the New Student Account Name
* Enter the New Student Account Password

.. image:: ../_resources/02_FSetup_Student.png

* Enter the New jadmin Account Password

.. image:: ../_resources/03_FSetup_jadmin.png

* Enter the Current Date (YYYYMMDD)
* Enter the Current Time (HH:MM) in 24 Hour format


.. image:: ../_resources/04_FSetup_DateTime.png

.. note::

    Once you have entered all the information, the script should conclude.*

6. Once the script concludes, close the Terminal Application.

.. note::

    In the event that information is incorrect when entered or was incorrectly entered, refer to the Changing Setup Values Document for more details on methods and commands to use to correct the information mis-entered.