# openBIS Importer Toolset (oBIT)

The [openBIS Importer toolset](https://wiki-bsse.ethz.ch/display/oBIT) is a tightly integrated collection of tools that allows for the semi-automated, semi-unsupervised registration of annotated datasets into [openBIS](https://sis.id.ethz.ch/software/openbis.html) directly from the acquisition stations; but it also extends openBIS itself with custom data viewers and server-side core plug-ins packaged into two new core technologies for flow cytometry and microscopy.

## Selected documentation:

* (Poster, 14MB) [Swiss Research Data Day (2018)](https://wiki-bsse.ethz.ch/display/oBIT/openBIS+Importer+Toolset?preview=/143301256/161088589/SwissResearchDataDay2018.pdf)
* (Slides, 10MB) [3rd OpenBIS user Group Meeting (2016)](https://wiki-bsse.ethz.ch/display/oBIT?preview=/143301256/144441348/oBIT.pdf)

## Current release: 1.1.0

Please follow the links below for the detailed changelog.

### Client-side components

The client-side components of oBIT are installed and configured on each acquisition instrument. Please use the **oBIT Installer** on Windows machines:

* [oBIT Installer](https://github.com/aarpon/obit_installer/releases/latest)

Notice that oBIT requires Java 8 to run. The [oBIT Installer](https://github.com/aarpon/obit_installer/releases/latest) can optionally take care of downloading it at setup.

### Server-side components (integrated into openBIS)

The **Microscopy** and **Flow Cytometry Core Technologies** are officially distributed along with openBIS since version 16.05.

## Development

The following is the list of all repositories that comprise the openBIS Importer Toolset.

### Client-side components

* oBIT Installer: https://github.com/aarpon/obit_installer
* Annotation Tool: https://github.com/aarpon/obit_annotation_tool
* Datamover: https://wiki-bsse.ethz.ch/display/DMV/Download+Page+Datamover
* Datamover-as-a-Windows-Service Wrapper: https://github.com/aarpon/obit_datamover_jsl

### Server-side components

* Microscopy Core Technology: https://github.com/aarpon/obit_microscopy_core_technology
* Flow Cytometry Core Technology: https://github.com/aarpon/obit_flow_core_technology
* Shared Core Technology: https://github.com/aarpon/obit_shared_core_technology
