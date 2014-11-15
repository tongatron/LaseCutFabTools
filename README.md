#LaseCutFabTools#

This is the alfa version of laserCut useful tools for Rhinoceros.

##Requirements##

- **McNeel Rhinoceros 5**

-  **Python 2.7 or above**  
[www.python.org/download](https://www.python.org/download)

##List of Tools##
- **TIME**  
estimate time of laserCut working.

- **BOX MAKER**  
this is a parametric notched box generator for laserCut.

- **JOINS MAKER**  
given a line generates a notched joins.

- **BENDING WOOD**  
this is a parametric Kerf pattern (linear version) generator, for wood bending with a lasercut
  http://www.gedankensuppe.de/kerf-bending-patterns.
  
##How to install##
####Windows####
Screencast install tutorial: [ vimeo.com/95678423]( http://vimeo.com/95678423)  

You need to put the .py files in a folder on your pc and add a toolbar and a button for each of one tool.

Advised position of the folder under windows OS:   *C:\Users\_yourPcName_\AppData\Roaming\McNeel\Rhinoceros\5.0\scripts\LaseCutFabTools*

Put in this folder all of the 4 .py files.  

Right click on the Rhino Toolbar > click on NewTab > NewButton:

- in Appearance setting you can import a bitmap icon of the button
- in text fill it with the name of the button
- in tooltip fill it with the description of the command
- in command you will need to write: RunPythonScript. Then select the Python script (*C:\Users\_nameOfYourUser_\AppData\Roaming\McNeel\Rhinoceros\5.0\scripts\LaserPlug-in\_nameOfPythonFile_*).  
Example:  RunPythonScript (*C:\Users\stefano\AppData\Roaming\McNeel\Rhinoceros\5.0\scripts\LaserPlug-in\Box_Maker.py*)
	
####Mac OSX####
You can use Ironpython to run python scripts, download here and install: [www.rhino3d.com/download/IronPython/5.0/wip](http://www.rhino3d.com/download/IronPython/5.0/wip)

Every time you need to launch a Tool:

1. on Rhinoceros, write “RunPythonScript” on the command box and click Enter to run.  

2. select the Python script you want to launch (ex. “Box_Maker.py"), located inside the folder “LaseCutFabTools-master”.
  

==============
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Licenza Creative Commons" style="border-width:0" src="http://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">LaserCutFabTools</span> di<a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/paDIYs/LaseCutFabTools" property="cc:attributionName" rel="cc:attributionURL">Stefano Paradiso</a> è distribuito con Licenza <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribuzione - Non commerciale - Condividi allo stesso modo 4.0 Internazionale</a>.
