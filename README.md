# ebeam_air
Geant4 simulation of electron beam in air

Running this project requires an installation of Geant4 (https://geant4.web.cern.ch/).

To build, source `geant4.sh` and `geant4make.sh`, then:

```
cmake .
make
cp $G4WORKDIR/bin/$G4SYSTEM/ebeam_air .
```

Running the executable `ebeam_air` initializes the simulation. An example run can be found in `run1.mac` (executable interactively with `/control/execute run1.mac`), and visualization settings are contained in `vis.mac`.
