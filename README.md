# RVIA

Runtime verification of interactions using automata.

### Version 0.1.0

(started September 2025)

## Executable

The executable for Windows is in ./bin/.
Executables for Linux and Mac (and a copy of the Windows one) are available on figshare (anonymous link) : https://figshare.com/s/79d06f993260133d85e0

Not for distribution.

Windows version compiled on Windows 11.

Linux version compiled on Ubuntu 24.04.

Mac version compiled on Mac OS Sequoia 15.5.

## Commands

To see all commands

```powershell
./bin/rvia.exe --help
```


To go to the first sample directory
```powershell
cd ./Experiments/Article/NFA1
```

From the sample directory, to call the centralized procedure on an NFA and a folder of multitraces (e.g. NFA1 and the corresponding Pass folder). Remove "-q" to see the time taken for each individual multitrace of the folder.

```powershell
../../../bin/rvia.exe analyze_centralized nfa_1.timbuk Pass/ -q
```

To call the semi-centralized procedure on an NFA and a folder of multitraces (e.g. NFA1 and the corresponding Pass folder). Remove "-q" to see the time taken for each individual multitrace of the folder.

```powershell
../../../bin/rvia.exe analyze_semicentralized nfa_1.timbuk Pass/ -q
```

To produce an NFA (e.g. NFA1) as a dot file
```powershell
../../../bin/rvia.exe draw nfa_1.timbuk -q
```
