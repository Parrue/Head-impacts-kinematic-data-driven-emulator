# Head impacts kinematic data-driven emulator


## Table of Contents

- [Introduction](#introduction)
- [Before Installation](#Before-Installation)
- [INPUT and OUTPUT of the program](#INPUT-and-OUTPUT-of-the-program)
- [Installation Guideline](#Installation-guidelines)
- [Running the Program](#running-the-program)


## Introduction

A data-driven emulator of head impacts kinematic, based on on-field measured kinematic data from contact sports (American football, mixed martial arts and boxing).

The generated kinematic data will be composed by 3D linear acceleration, angular velocity and angular acceleration with time length of 100 ms and sample frequency of 1000Hz. 

## Before Installation

In order to run the stand-alone program you need to install MATLAB Runtime R2020a (9.8). You can download it from https://www.mathworks.com/products/compiler/matlab-runtime.html.

## INPUT and OUTPUT of the program

> INPUT

The data-driven emulator requires INPUT parameters from the user. Those parameters are:

- **Number of required data (n)**: The number of linear acceleration, angular velocity and angular acceleration impulses desired to be generated.
- **Number of basis modes (k)**: The number of modes used for generating data. The maximum modes depends on the parameter: For angular velocity is 15, for angular acceleration is 21 and for linear acceleration is 29.
- **Magnification (m)**: TO BE COMPLETED.

> OUTPUT

The Output will be a set of 9 .csv files. Each one contains a matrix of 100xn in which each column represent a single impulse of 100ms of duration, with the following nomenclature:

- LaAP:  Linear acceleration Antero-Posterior direction.
- LaLat: Linear acceleration Lateral direction.
- LaIS:  Linear acceleration Inferior-Superior direction.
- oCor:  Angular velocity Coronal plane.
- oSag:  Angular velocity Sagittal plane.
- oAx:   Angular velocity Axial plane.
- aCor:  Angular acceleration Coronal plane.
- aSag:  Angular acceleration Sagittal plane.
- aAx:   Angular acceleration Axial plane.

## Installation guideline

After the installation of MATLAB Runtime you can install the Data-driven Emulator. Please download the executable 

## Running the program

