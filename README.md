# Automated-Structure-Modifications

This repository provides a set of Python scripts and tools to automate structural modifications. 
Python codes Using ASE, Pymatgen, and etc.

- **slice-CIFs** unit cells into equal sub‑cells. Or keep only the region within specified X×Y×Z limits. (using Pymatgen, Input file: crystallographic CIF files) 
- **conversions** to calculate center of mass of a VASP file (POSCAR) and convert structures to different formats (VASP, CIF, XYZ). (using ASE, Input file: POSCAR,CIF, and XYZ)
- **rotation-structures** This subdirectory contains a Python script for performing 3D coordinate rotation about the centroid (i.e., the mean of all input coordinates). Reads a list of coordinates from rotation_file.xlsx and writes the rotated coordinates to rotatedfile.xlsx.



### Explore and extend these workflows for my materials‑science pipelines.

