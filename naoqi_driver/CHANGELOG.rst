^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package naoqi_driver
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.4.1 (2014-11-13)
------------------
* added speech dynamic reconfigure
* bugfix: naoqi migration
* Init ros node before getting parameters
  Fix a problem where the pip and pport parameters are always set to their
  default values when using the parameter server and not command line arguments.
* Search for free port for broker
  Setting the local port to zero causes the broker to search for a free port.
  In nao_robot/nao_apps/nao_tactile.py this technique is used to make the broker
  search for a free port. However this does not appear to be a documented
  by aldebaran.
* Update for naoqi version < 2.0
* Contributors: Edgar Riba, Jon Dybeck, Karsten Knese

0.4.0 (2014-11-06)
------------------
* fix install file for cmake hook
* removed wrong install routine
* introduce replace tag in package.xml
* cleanup
* moved to pose_controller.py in nao_robot
* quickfix for renaming
* renamed naoqi_sensors
* cmake extras hooks
* api change
* remove and renaming
* renamed subfolders for naoqi_*
* Contributors: Karsten Knese
