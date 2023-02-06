# TARDIS-configs
Repository of various TARDIS-SN configuration files.

This repository contains various TARDIS-SN configuration files ranging in purpose.  These configuration files may be used as examples for running TARDIS-SN to model different types of astrophysical sources or using extended physics features present within TARDIS-SN.  Some configuration files may be results or templates used in scientific publications for reproducibility.  The organizational strucutre of this repository is as follows:

```
<SOURCE>
│   README.md
└───<SUBSOURCE>
    │   README.md
    └───<OBJECT TYPE>
        │   README.md
        └───models
        │   │   README.md 
        │   └───model1
        │   │   │   README.md
        │   │   │   model1.yml
        │   │   │   [model1.csvy]
        │   │   
        │   └───model2
        │   │   │   ...
        │   │   
        │   └───... 
        │   
        └───templates
            │   README.md 
            └───template1
            │   │   README.md
            │   │   template1.yml
            │   │   [template1.csvy]
            │   
            └───template2
            │   │   ...
            │   
            └───... 
            

```

### SOURCES:

`publications`: Configuration files that have been used in published scientific work.  Subsources are named by their respective publication source.

`gsoc`: Configuration files related to explicit Google Summer of Code acitivites.  Subsources correspond to their respective GSoC projects.

`examples`: Configuration files that serve as examples of how to run TARDIS for different types of objects in different run modes.  May contain documentation related configuration files.  Subsources correspond to their respective intended usage.

### OBJECT TYPES:

The type of object that the configuration files are intended to model.  This may be a spectral type, individual object, or other kind of designation.  These may contain subfolders for more specificity.  For example, a possible directory layout may be `Type Ia/1991T-likes/SN1999dq/`

### Templates and Models

`templates`: Configuration files used as templates for generating parameterizaed configuration files.  These config files may not be complete or valid.

`models`: Complete and valid TARDIS-SN config files that are ready to run.



