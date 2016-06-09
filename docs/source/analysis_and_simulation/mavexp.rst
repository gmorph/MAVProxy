=============
MAVExplorer
=============

The MAVExplorer tool is an interactive tool for graphing APM logfiles.

Under Linux, it can be accessed by:

.. code:: bash

    mavexplorer.py inputlog.tlog
    
Under Windows, it can be found in the Start Menu with the rest of MAVProxy.

Use the MAVExplorer->Open menu to open tlog files to graph.

.. figure:: mavexp1.png

The Graphs menu will automatically populate based upon the available packets in the logfile.

To narrow down the log file to a particular phase of the logfile, select the relevant mode from the FlightMode menu. Any future graphs will only cover the selected section of the flight.

.. figure:: mavexp2.png

.. note::

    Under Windows, it may take some time for MAVExplorer to process the graphs when plotting them.
    
The Display menu contains methods for displaying a map of the GPS points of the logfile and reloading the logfile. Additionally there are methods for creating and saving custom graphs, using the same notation as with the :doc:`graph <../modules/graph>` module in MAVProxy.

.. note::

    Saving custom graphs is not currently available on Windows.
