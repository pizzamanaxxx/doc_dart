DART-Lux LiDAR uses DART-RC input parameters and not DART-Lux input parameters. It gives most DART-RC products (waveform/discrete return/photon counting) for any instrumental (terrestrial / satellite / airborne,...) and environmental (vegetation/urban/mountain/atmosphere/3D object/turbid/facet) configurations.

- ***Single-pulse waveform products***
    - <u>*Waveform (same as DART-RC)*</u>: `pulse.txt` ([here](../../../Format_DART_files/3-DART_RC/dart_rc.md#output-files-single-pulse)), `LIDAR_DART_wave.txt` (`LIDAR_DART_wave_1stOrder.txt`) ([here](../../../Format_DART_files/3-DART_RC/dart_rc.md#output-files-single-pulse)), `LIDAR_CONVOLVED_wave.txt` (`LIDAR_CONVOLVED_wave_1stOrder.txt`) ([here](../../../Format_DART_files/3-DART_RC/dart_rc.md#output-files-single-pulse)).
    - <u>*Photons image*</u>:
        - ima_camera_lidar_i_j.mp#: number of returned photons projected at LiDAR location; i and j the grid line (i.e., azimuth) and column (i.e., range) of lidar pulses (i = j = 0 for single pulse).
        - ima_camera_lidar_i_j_bin=k.mp#: the number of returned laser photons at k bin.

- ***Multi-pulse waveform products (same as DART-RC)***
`LIDAR_IMAGE_panel.txt` ([here](../../../Format_DART_files/3-DART_RC/dart_rc.md#output-files-multi-pulse)), `LIDAR_IMAGE_FILE.binary` ([here](../../../Format_DART_files/3-DART_RC/dart_rc.md#output-files-multi-pulse)), `LIDAR_IMAGE_STATUS.txt` ([here](../../../Format_DART_files/3-DART_RC/dart_rc.md#output-files-multi-pulse)).
- ***Multi-pulse discrete return / photon counting products ***(same as DART-RC): `DetectedPoints.txt` ([here](../../../Format_DART_files/3-DART_RC/dart_rc.md#output-files-multi-pulse), [here](../../../Format_DART_files/3-DART_RC/dart_rc.md#output-files-multi-pulse))
- ***Solar noise products***
    - <u>*`Solar_noise.txt` (same as DART-RC)*</u> ([here](../../../Format_DART_files/3-DART_RC/dart_rc.md#output-files-multi-pulse)): i, j, average sun radiance $(W/m^2/sr/\mu m)$, LiDAR signal due to sun only (W), LiDAR signal per bin (J), Number of sun photons per bin.
    - <u>*`rad0.txt`*</u> (same as DART-RC) ([here](../../../Format_DART_files/3-DART_RC/dart_rc.md#output-files-multi-pulse)): average sun radiances of nodes.
    - <u>*Solar image*</u>: ima_camera_SN_i_j.mp#: the number of returned solar photons projected at the LiDAR position.
