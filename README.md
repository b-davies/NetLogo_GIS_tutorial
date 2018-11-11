# NetLogo_GIS_tutorial_v1

This software is associated with a forthcoming publication:

Davies, B., Romanowska, I., Harris, K., and S. Crabtree, In press. Combining Geographic Information Systems and Agent-Based Models in Archaeology: A step-by-step guide for using agent-based modeling in archaeological research (Part II of III). Accepted to Advances in Archaeological Practice.

The stable release can be downloaded as a zip here: 
[![DOI](https://zenodo.org/badge/131584168.svg)](https://zenodo.org/badge/latestdoi/131584168)

This is a model used in Davies et al. (2019) based on the work of This work draws on a neutral model of stone procurement by Brantingham (2003), and builds directly on work developed in Romanowska et al. (2019).

## HOW IT WORKS

During each time step, the turtle moves to one of the surrounding patches or stays on its current patch. If the agent is at an elevation that is less than the preset elevation-theshold, it will perform the movement operation once; otherwise, it will perform the movement
Turtles possess a toolkit which contains stone objects that originate from a particular quarry. After each sequence of movements, if the turtle has any objects in its toolkit, it will discard one object, which becomes part of the assemblage of the local patch.
A set of quarry locations exist in the map. If the turtle crosses over a patch with a quarry, it will replenish its toolkit with stone objects from that quarry up to a preset max-carry limit.
After a period of time (time-limit), the simulation stops, and the patches with stone objects in their assemblages are shaded red according to the number of artefacts.

## HOW TO USE IT
This simulation is used to demonstrate how to import, use, and export GIS data for archaeological applications. In order to use this model, the following list of files need to be included in the same directory as the .nlogo file: dem.asc dem.asc.aux.xml dem.prj quarries.dbf quarries.prj quarries.qpj quarries.shp quarries.shx


## CREDITS AND REFERENCES
Brantingham, P. J. 2003. “A Neutral Model of Stone Raw Material Procurement.” American Anthropologist 68 (3): 487–509.

Davies et al. (2019) “Combining Geographic Information Systems and Agent-Based Models in Archaeology. A step-by-step guide for using agent-based modeling in archaeological research (Part II of III)” Advances in Archaeological Practice

Romanowska et al. (2019) “Agent-based Modeling for Archaeologists. A step-by-step guide for using agent-based modeling in archaeological research (Part I of III)” Advances in Archaeological Practice

