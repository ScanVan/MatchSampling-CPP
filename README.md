## Scanvan Project

The ScanVan project is a share initiative between the EPFL and the HES-SO Valais funded by the FNS. The goal of the project is to design and build a spherical camera in the field of mass digitisation of cities and environment for 3D/4D model computation. Along with the camera built, the project also consist in the theoretical definition of new photogrammetric algorithms taking advantage of the spherical approach of the camera toward high efficiency computation of models.

## This repository

This repository contains a code for re-sampling set of triplet matches using a proximity constraint to eliminate matches with too close subsequent features on the central image of the triplet. This allows to have a better distribution of the matched features avoiding too large density on parts of the images.

## Copyright and License

**ScanVan Project** - Nils Hamel <br >
Copyright (c) 2016-2019 EPFL, HES-SO Valais

This program is licensed under the terms of the GNU GPLv3.

## Dependencies

This repository comes with the following package dependencies (Ubuntu 16.04 LTS) :

* build-essential

The code documentation is built using Doxygen.

## Compilation

To build the project, including the sub-modules and third parties, use make with the following targets :

    $ make clean && make all
