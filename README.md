To launch the full transformation chain, run the ANT file launch-all.xml: 
- right-click on launch-all.xml
- Run as->Ant Build

Note: the ANT file has to run in same JRE of Eclipse to access the ATL tasks.

The transformation log is shown in the Eclipse Console, including timings for all the transformation steps.

Results are generated in the following folders:
- source-models: for JaMoPP-generated java models;
- results: for all the phases of the program dependency graph generation;
- validation: for validation models and results.

To simplify the evaluation of the solution we developed a validation wizard (already installed in the SHARE demo). 
To start the wizard select New->Other...->Flowgraphs->PDG Validation Wizard and select a PDG file 
(-DataFlowGraph.xmi) and a PDG validation file (.val).