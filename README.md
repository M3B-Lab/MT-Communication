# Architecture-Encoded Communication in Microtubules
This repository contains all the necessary data to replicate the findings of the paper "Architecture-Encoded Mechanics and Communication in
Microtubules: A Multiscale Computational Perspective".

The input data to replicate the simulations are organized as follows:

- `01-MDSimulations`: Folder containing the mdp files, topologies and starting structures for the MD simulations  (3 replicates).*

  - `11PF/`: Folder containing the files for the 11 protofilament system.
 
    - `S1/`: Files for sheet representing S1 system (far from MT seam).

    - `S2/`: Files for sheet representing S2 system (MT seam).
   
    - `S3/`: Files for sheet representing S3 system (MT seam).

  - `16PF/`: Folder containing the files for the 16 protofilament system.

- `02-ENM/`: Folder containing the starting files and templates to reconstruct the MT rings.

  - `RingTemplate/`

    - `11PF/`: Folder containing the files for the 11 PF system.
   
    - `13PF/`: Folder containing the files for the 13 PF system.
   
    - `16PF/`: Folder containing the files for the 16 PF system.


* NOTE: For the simulation files related to the 13 PF system, please refer to the repository available at https://github.com/M3B-Lab/Tubulin-PSN 
