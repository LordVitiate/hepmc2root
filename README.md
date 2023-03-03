# hepmc2root
Python program to convert a text file of events in HepMC2 format to a simple ROOT file.
Prerequisites of the converter

```bash
	pip install PyRoot
```

## Example
Go to the *example* directory and do
```bash
	source setup.sh
	pyroot ../bin/hepmc2root.py susy200.hepmc
```
which will create the file susy200.root that can be analyzed with a standard TNM *analyzer*. 
