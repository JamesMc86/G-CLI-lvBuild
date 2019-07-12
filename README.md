# G-CLI-lvBuild
A LabVIEW build tool for the G CLI interface

# Parameters

## Optional

-buildNumber: Sets the build number for the specification, keeping the others as they already are.

-versionNubmer: Sets the full version number in the format "d.d.d.d"

-target: Name of project target to build for. Defaults to "My Computer"

## Required

* Project Path
* Build Specification (If missing, all will build but build numbering will error.)

## Example Call

g-cli --lv-ver 2015 lvBuild -- -buildNumber 4 "LabVIEW Source\MyProject.lvproj" myExe


