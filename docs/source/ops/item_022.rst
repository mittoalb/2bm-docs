Computing 
=========

The following computers are in use in the Imaging Group:

.. _cluster_folder: https://anl.box.com/s/cwqbvet2qv8239nhrof0qemyohd0jho3
.. _cluster: https://anl.box.com/s/uysvb5ujnlugmd16r2f6o10fem9rjgvr
.. _cluster_01: https://anl.box.com/s/oc9g49r6an1lcwh0d5gzisno6ef5yni1
.. _cluster_02: https://anl.box.com/s/7onv5ju2rt42w15uz689pbuslfelpvz9
.. _disk_array: https://anl.box.com/s/zzyvv7w80ltwbtf09zrjiqiw7ak6i7ge
.. _cluster_quote: https://anl.box.com/s/j7wz6li4afoq2gs5g8feehmmz8q7whuy
.. _cluster_quote_01: https://anl.box.com/s/06nkozbmkhu5qsi61njcgm1qs3ug8pcg
.. _cluster_quote_02: https://anl.box.com/s/hz9l2whlju2a81tyr4k9e07ukc8m4zkn
.. _disk_array_quote: https://anl.box.com/s/sbft8cbt2xcpzuuvikixr82dn9jf6zog


Data Analysis and Storage
-------------------------


+-----------+--------------+---------------+-----------------+---------------------------------+----------------------+
| Station   | Name         | Product       | Part list       |      Model                      |      Quote           |
+-----------+--------------+---------------+-----------------+---------------------------------+----------------------+
| 2-BM      | tomo 1-2     | MNJ15421064   | `cluster`_      |  Supermicro 740GP-TNRT node     | `cluster_quote`_     |
+-----------+--------------+---------------+-----------------+---------------------------------+----------------------+
| 2-BM      | tomo 3       | MNJ15421064   | `cluster_01`_   |  Supermicro 740GP-TNRT node     | `cluster_quote_01`_  |
+-----------+--------------+---------------+-----------------+---------------------------------+----------------------+
| 2-BM      | tomo 4-5     | MNJ16235754   | `cluster_02`_   |  Supermicro 220GQ-TNAR+ node    | `cluster_quote_02`_  |
+-----------+--------------+---------------+-----------------+---------------------------------+----------------------+
| 2-BM      | disk array   | MNJ15508749   | `disk_array`_   |  SYS-220U-TNR Storage           | `disk_array_quote`_  |
+-----------+--------------+---------------+-----------------+---------------------------------+----------------------+


Data Collection
---------------

+-----------+--------------+-------------------+-----------------+--------------------------+---------------------+
| Station   | Name         |      Model        |  Product No.    |    Serial No.            |        Manual       |
+-----------+--------------+-------------------+-----------------+--------------------------+---------------------+
| 2-BM-A    | pg10ge       |  HP Z8 G4         | 3GF37UT#ABA     |  `pg10ge label`_         |     `pg10ge SM`_    |
+-----------+--------------+-------------------+-----------------+--------------------------+---------------------+
| 2-BM-B    | lyra         |  HP EliteDesk 800 | P4K18UT#ABA     |  `lyra label`_           |     `lyra SM`_      |
+-----------+--------------+-------------------+-----------------+--------------------------+---------------------+

For each machine part list at purchase time and for the list of supported hardware enter the serial numeber in the `HP support <https://partsurfer.hp.com/Search.aspx>`_ web page.

.. _pg10ge label: https://anl.box.com/s/oslaky958be3vyifda2xyq4tv0v9v7pz
.. _pg10ge SM: https://anl.box.com/s/m1u8o62wbr27n26iotfnbhgpncwsapcq
.. _lyra label: https://anl.box.com/s/lrjiwsfzwbe51gueb6vpyinqav86qx6o
.. _lyra SM: https://anl.box.com/s/dv0ub0gdjhs7q3h50ehgro6gaesbxcjf


Data Visualization
------------------

The default computer is **handyn** where the following software is installed:

Raw Data
~~~~~~~~

To view the tomographic raw data we suggest to install `Fiji <https://imagej.net/Fiji>`_ and add 
the `HDF plugin <https://github.com/paulscherrerinstitute/ch.psi.imagej.hdf5>`_

Other options are `hdfview <https://support.hdfgroup.org/products/java/hdfview/>`_ or 
`argos <https://github.com/titusjan/argos>`_

To view the tomographic raw data we suggest to install `Fiji <https://imagej.net/Fiji>`_ and add 
the `HDF plugin <https://github.com/paulscherrerinstitute/ch.psi.imagej.hdf5>`_

Other options are `hdfview <https://support.hdfgroup.org/products/java/hdfview/>`_ or 
`argos <https://github.com/titusjan/argos>`_


Dragonfly
~~~~~~~~~


After your data are reconstructed you can visualize using `Dragonfly <https://www.theobjects.com/dragonfly/index.html>`_.

Login at the beamline Linux machine and then type::

    [tomo@handyn]$ cd /local/tomo/software/dragonfly
    [tomo@handyn]$ ./Dragonfly

