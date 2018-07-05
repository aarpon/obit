# openBIS Importer Toolset (oBIT)

The [openBIS Importer toolset](https://wiki-bsse.ethz.ch/display/oBIT) is a tightly integrated collection of tools that allows for the semi-automated, semi-unsupervised registration of annotated datasets into [openBIS](https://sis.id.ethz.ch/software/openbis.html) directly from the acquisition stations; but it also extends openBIS itself with custom data viewers and server-side core plug-ins packaged into two new core technologies for flow cytometry and microscopy.

## Current release: 1.1.0

### Client-side components

The client-side components of oBIT are installed and configured on each acquisition instrument.

* [Annotation Tool](https://github.com/aarpon/obit_annotation_tool/releases/latest)

To install, it is recommended to use the [oBIT Installer](https://github.com/aarpon/obit_installer/releases/latest).

### Server-side components (integrated into openBIS)

* [Microscopy Core Technology](https://github.com/aarpon/obit_microscopy_core_technology/releases/latest)
* [Flow Cytometry Core Technology](https://github.com/aarpon/obit_flow_core_technology/releases/latest)
* [Shared Core Technology](https://github.com/aarpon/obit_shared_core_technology/releases/latest)
