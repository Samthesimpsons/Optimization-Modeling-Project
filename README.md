# Optimization-Modeling-Project
SUTD 40.011 Data and Business Analytics Project

**Project Title:** Simulation Model for Mobile Cleaning Teams

**Description:** My group was tasked to create a model for Changi Airport Group to optimize the amount of manpower resources needed at the airside.

**Tools used:**
1. **SQLite** to hold the flight data
2. **QGIS** for network analysis of the Changi Aerodome map
3. **Excel** for the Optimization Model


#!/bin/bash

#File: tree-md

tree=$(tree -tf --noreport -I '*~' --charset ascii $1 |
       sed -e 's/| \+/  /g' -e 's/[|`]-\+/ */g' -e 's:\(* \)\(\(.*/\)\([^/]\+\)\):\1[\4](\2):g')

printf "# Project tree\n\n${tree}"
