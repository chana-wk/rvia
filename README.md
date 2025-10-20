# RVIA

Runtime verification of interactions using automata.

### Version 0.1.0 

(started September 2025)

## Commands


To call the centralized procedure on an NFA and a folder of multitraces (e.g. NFA1 and the corresponding Pass folder). Remove "-q" to see the time taken for each individual multitrace of the folder.

``
.\rvia.exe ac .\Experiments\NFA1\nfa_1.timbuk .\Experiments\NFA1\Pass\ -q 
``


To call the semi-centralized procedure on an NFA and a folder of multitraces (e.g. NFA1 and the corresponding Pass folder). Remove "-q" to see the time taken for each individual multitrace of the folder. 

``
.\rvia.exe as .\Experiments\NFA1\nfa_1.timbuk .\Experiments\NFA1\Pass\ -q 
``


To draw an NFA (e.g. NFA1) as a .dot file

``
.\rvia.exe draw .\Experiments\NFA1\nfa_1.timbuk -q 
``


See all commands

``
.\rvia.exe help
``