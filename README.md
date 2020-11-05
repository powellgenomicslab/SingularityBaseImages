# SingularityBaseImages

A repo for singularity images. This is linked to singularity hub and all results can be pulled from there.

## Singularity Hub Images

- Singularity.R363_python368

  - To pull: `singularity pull drneavin/SingularityBaseImages:r363_python368`
  - Contains:
    - R 3.6.3
    - python 3.6.8
    - conda
    - Some basic R packages (see the definition file to see all installed)
    - Some basic python package (see the definition file to see all installed)
    
- Singularity.R4_python368

  - To pull: `singularity pull drneavin/SingularityBaseImages:r4_python368`
  - Contains:
    - R 4.0.3
    - python 3.6.8
    - conda
    - Some basic R packages (see the definition file to see all installed)
    - Some basic python package (see the definition file to see all installed)
  
- Singularity.TxnDoubletDetection

  - To pull: `singularity pull drneavin/SingularityBaseImages:txndoubletdetection`
  - Built on top of `Singularity.R4_python368` image
  - Also contains:
    - DoubletDetection
    - DoubletDecon
    - DoubletFinder
    - scds
    - scrublet
    - scDoubletFinder
    - solo

  
  
