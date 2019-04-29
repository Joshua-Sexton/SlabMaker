# SlabMaker

Consist of two part:
1. TransCell
Transformation between primitive cell and unit cell.

2. SlabMaker
Build slab models for crystal surfaces.

Input unit cell and output slab models

use VASP POSCAR format
```
Si C Unit cell: comment goes here
1.0
        4.3480000496         0.0000000000         0.0000000000
        0.0000000000         4.3480000496         0.0000000000
        0.0000000000         0.0000000000         4.3480000496
   Si    C
    4    4
Direct
     0.000000000         0.000000000         0.000000000
     0.000000000         0.500000000         0.500000000
     0.500000000         0.000000000         0.500000000
     0.500000000         0.500000000         0.000000000
     0.250000000         0.250000000         0.250000000
     0.750000000         0.750000000         0.250000000
     0.750000000         0.250000000         0.750000000
     0.250000000         0.750000000         0.750000000

```
