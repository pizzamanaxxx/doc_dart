# DART User's Manual (5.9.6)

<img src="./media/logo.png">

## 1- Features

- The 3 DART modes and 2 light modes
- Edition of DART simulations
- Display and processing tools
- Format of input/output DART files
- Work packages

## 2- The Application

[DART](https://dart.omp.eu)  simulates passive remote sensing (RS) and LiDAR signals and also the radiative budget (RB) of urban and natural landscapes. It traceslight in landscapes and atmosphere with 2 light-modes. The Forward light-mode voxelizes landscapes and traces light with DOM (discrete ordinate method) or MC (Monte Carlo) methods. The Bi-directional light-mode does not voxelize landscapes and traces light with bi-directional MC methods. DART has 3 modes:

- Passive RS and RB: reflectance and brightness temperature images, albedo, SIF (sun induced fluorescence),... This mode is called DART-FT for the DOM Forward light-mode and DART-Lux for the Bi-directional light-mode. 
- LiDAR: waveform, photon counting, point cloud. This mode is called DART-RC for the MC Forward light-mode, and DART-Lux for the Bi-directional light-mode.
- Monte Carlo: reflectance of landscapes without atmosphere. It uses very basic MC methods and is rarely used.

## 3- Structure of the documentation

DART (Discrete Anisotropic Radiative Transfer) models radiative transfer (RT) from the ultraviolet to the thermal infrared, for simulating the radiation budget (RB), including sun-induced chlorophyll fluorescence (SIF), and remote sensing (RS) signals (Lidar, spectro-radiometer images) of natural and urban surfaces (*i.e.*, Earth scenes) with atmosphere. This document[^1] explains DART functionalities and how to use them:

- [Chapter 1](./Remote_sensing/remote_sensing.md): Overview of major RT models, and DART, for studying land surfaces with remote sensing.
- [Chapter 2](./DART_model/dart_model.md): DART functionalities (scene creation, sensor configuration,...) from the Graphic User Interface (GUI).
- [Chapter 3](./DART_functionalities_and_products/1-File_architecture/file_architecture.md): Tools for managing DART and its results, with and without the GUI.
- [Chapter 4](./Format_DART_files/1-All_dart_modes/all_dart_modes.md): Format of most DART inputs and outputs.
- [Chapter 5](./General_advices/general_advices.md): Advices you can read in order to have a better usage of DART.
- [Chapter 6](./Physical_bases/physical_bases.md): List of physical concepts or measures mainly used in DART.
- [Chapter 7](./Tutorials/T0/t0.md): Formerly named Work Packages, they are Tutorials (WP0 : overview, WP1: reflectance, WP2: thermal emission,.. ) to practice DART and better understand the physics of RS . Their simulations are in the DART web site. Beginners should start with WPs 1 and 2.

[^1]: Regularly updated. In addition, the "DART Handbook" presents some physics of DART RT modeling
