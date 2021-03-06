sIBL_GUI For XSI - 3.1.0
========================

.. .changes

Changes
=======

3.1.0 - Stable
--------------

-  Refactor addon for sIBL_GUI 4.0.0.


3.0.0 - Alpha
-------------

-  New Addon for sIBL_GUI 3:
   -  sIBL_GUI is not provided anymore with the Addon.
   -  New preferences property with settings to define sIBL_GUI executable.
   -  Shortcuts to useful sIBL_GUI related urls.

2.1.1 - Stable
--------------

-  Repackaged the XSI Addon with the last Stable version of sIBL_GUI. Check sIBL_GUI Thread for more informations: sIBL_GUI Thread

2.1.0
-----

-  MR Template has been updated: a Custom Property gather some controls for the Rendering, the Components are in Layers now.
-  Repackaged the XSI Addon with the last Stable version of sIBL_GUI. Check sIBL_GUI Thread for more informations: sIBL_GUI Thread

2.0.8
-----

-  Repackaged the XSI Addon with the last Stable version of sIBL_GUI. Check sIBL_GUI Thread for more informations: sIBL_GUI Thread

2.0.7
-----

-  Repackaged the XSI Addon with the last Stable version of sIBL_GUI. Check sIBL_GUI Thread for more informations: sIBL_GUI Thread

2.0.6
-----

-  Repackaged the XSI Addon with the last Stable version of sIBL_GUI. Check sIBL_GUI Thread for more informations: sIBL_GUI Thread

2.0.5
-----

-  Repackaged the XSI Addon with the last Stable version of sIBL_GUI. Check sIBL_GUI Thread for more informations: sIBL_GUI Thread

2.0.2
-----

-  Corrected a bug where The GPS ".png" map wasn't properly copied from the Addon in the previous releases ( the GPS Map is now a .jpg ).

2.0.1
-----

-  Repackaged the XSI Addon with the last Stable version of sIBL_GUI. Check sIBL_GUI Thread for more informations: sIBL_GUI Thread

2.0.0
-----

-  Repackaged the XSI Addon with the last Stable version of sIBL_GUI. Check sIBL_GUI Thread for more informations: sIBL_GUI Thread

1.9.1
-----

-  Repackaged the XSI Addon with the last version of sIBL_GUI. Check sIBL_GUI Thread for more informations: sIBL_GUI Thread

1.4.0
-----

-  Repackaged the XSI Addon with the last version of sIBL_GUI. Support for sIBL V2 File Format. Check sIBL_GUI Thread for more informations: sIBL_GUI Thread

1.0.3
-----

-  Repackaged the XSI Addon with the last version of sIBL_GUI, lots of new features in sIBL_GUI. Check sIBL_GUI Thread for more informations: sIBL_GUI Thread

1.0.2
-----

-  Fixed a strange behavior in XSI Template where the JScript word "undefined" is not working as intended in Linux, I replaced it by "null" and seems that everything is back on tracks again ( Thanx To Yuri )!

1.0.1
-----

-  BugFix on sIBL_GUI_For_XSI.js: The launcher wasn't working when sIBL_GUI was deployed on a server ( with path like "\\Server" ). Thanx to Rob W. for reporting the bug!

1.0.0 - Stable
--------------

-  Update Code improvements and new features ( Feedback update, etc).
-  BugFix and improvements on sIBL_GUI.

0.9.8
-----

-  Added Update Scene option to the Template (Update Scene and Override User Tweaks Buttons). This basically enable you to update some part of the sIBL Setup and for example, use the background of one sIBL_Set, the reflection or the Sun of another one. There are a lot of combinations possible. The code is not entirely finished and don't fully apply on Sun for example.
-  Refactored some procedures.
-  BugFix and improvements on sIBL_GUI.

0.9.7
-----

-  Linux version should work. ( Well since I have an half-working XSI, I can't really tell... )
-  BugFix and improvements on sIBL_GUI.

0.9.6
-----

-  Thanks to Keksonja for busting the bugs!:]
-  BugFix and improvements on sIBL_GUI.
-  Corrected a possible crash when disabling Feedback creation.
-  Restored Background/Eye Texture behavior broken by last Template Release.
-  Background Texture is now visible in Viewport even if you don't choose create Background.

0.9.5
-----

-  BugFix and improvements on sIBL_GUI.
-  Code optimisation.
-  Added possibility to choose wich Passes you want to connect the sIBL File to ( Check the "Pass Selection Dialog" Button in the Template Attributes ).
-  Disabled the possibility to rotate the Feedback on the 3 axes (I don't manage to make the Environment Shader match the Feedback with 3 rotations axes), you can however still rotate it on Y to orient it.

0.9.4
-----

-  sIBL_GUI can now directly connect to XSI with sIBL_GUI_XSI_Server Addon! ( Was a real pain to do! )
-  Improved Template with:
   -  Progress Bar.
   -  Large part of the Code in Object Model. ( Faster execution )
   -  Physical Sun Shader.
   -  Use of XSI new Color Management. ( Don't forget to manually remove tonemapping nodes from your cameras if you have used previous releases of the Template )
-  Remote Connection Code, interface polishing, bugfix and improvements on sIBL_GUI.

0.9.3
-----

-  BugFix and improvements on sIBL_GUI.

0.9.2.2
-------

-  Found a way to directly launch the program from XSI ( Not through the .lnk file anymore ), should be better for Vista users.

0.9.2.1
-------

-  Bugfix on sIBL_GUI.

0.9.2
-----

-  Improvements and bugfix on sIBL_GUI.

0.9.1
-----

-  Bugfix on sIBL_GUI.

0.9.0
-----

-  Initial release of sIBL_GUI For XSI

.. .about

About
-----

| **sIBL_GUI For XSI** by Thomas Mansencal - 2008 - 2014
| **sIBL_GUI** by Thomas Mansencal - 2008 - 2014
| Copyright © 2008 - 2014 – Thomas Mansencal – `thomas.mansencal@gmail.com <mailto:thomas.mansencal@gmail.com>`_
| This software is released under terms of GNU GPL V3 license: http://www.gnu.org/licenses/
| `http://www.thomasmansencal.com/ <http://www.thomasmansencal.com/>`_