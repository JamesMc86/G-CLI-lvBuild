# G-CLI-lvBuild
A LabVIEW build tool for the G CLI interface

# Requirements

* LabVIEW 2014 or higher.

# lvBuild Command

## Optional

-buildNumber: Sets the build number for the specification, keeping the others as they already are.

-versionNubmer: Sets the full version number in the format "d.d.d.d"

-target: Name of project target to build for. Defaults to "My Computer"

## Required

* Project Path
* Build Specification (If missing, all will build but build numbering will error.)

## Example Call

g-cli --lv-ver 2015 lvBuild -- -buildNumber 4 "LabVIEW Source\MyProject.lvproj" myExe

## Usage Notes

### LabVIEW FPGA

This does not currently support FPGA builds. This is something we will look into as part of this in the future or an alternative tool.

### Build Location

By default the build location maybe the level above the project.


