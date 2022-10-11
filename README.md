# ABAP-to-PlantUML Diagrams

[![Language: ABAP](https://img.shields.io/badge/Language-ABAP-blue.svg?style=flat)](https://www.sap.com/developer/topics/abap-platform.html)

### Forked from [nomssi](https://github.com/nomssi/ABAP-to-PlantUML)
#### See original [Readme](https://github.com/nomssi/ABAP-to-PlantUML#readme) for details

### Delta
#### in [/class diagram/latest/zz_uml_class_export.prog.abap](https://github.com/PilotFlying/ABAP-to-PlantUML-SVG/blob/master/class%20diagram/latest/zz_uml_class_export.prog.abap)
 - Display programs, table types, and data elements (all still linked to a class, to be traversed by CL_UML_CLASS_SCANNER)
 - Selection screen option to omit traversal of standard SAP-package objects
 - Modified UML relation symbols with additional labels
 - Default plantUML service to svg image type (bypasses png truncation of large diagrams and allows for in-place browser zoom)
 - Display HTML using GUI window as container (full screen view possible)
 - Notes
   - CTRL-mouse roller works in GUI for zooming on the plantUML vector graphics (no loss of detail, as opposed to png)
   - GUI "save image as" defaults to ".png" but allows changing the extension to the correct ".svg"
