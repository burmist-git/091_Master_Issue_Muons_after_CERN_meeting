The points are presented in chronological order, as they were discussed. If a point is marked with the (closed) keyword at the end, it means it has already been addressed or is no longer relevant. If a point is marked with the (TBD) keyword at the end, it means it needs to be done and the algorithm is provided. If a point is marked with the (To clarify) keyword at the end, it means it needs to be done and the algorithm is NOT provided. The sentence __The test statement needs to be written and approved__ means that, in addition, the test procedure needs to be written. The keywords __ctapipe__ and __calibpipe__ specify the project to which it should be assigned.

**Every item has to be followed by a described test procedure.** It has been agreed to use UC templates for the test statements.

1) **From DPPS Level B Requirements Specification_stamped.pdf: 9.8.23 CTAO-B_DPPS-439 - Calibration of the Muon Analysis Using Simulations.**
The DPPS shall support calibrating the muon analysis against dedicated muon simulations that include all relevant shadow-casting parts of the telescope at their respective distances to the reflector.
    - Project : <ins>ctapipe</ins>
    - Status : **closed**
    - Test statement : bla bla bla

2) **From DPPS Level B Requirements Specification_stamped.pdf: 9.8.25 CTAO-B_DPPS-408 - Optical Throughput Uncertainty Estimation.**
The DPPS shall provide tools to estimate the statistical and systematic uncertainty of the optical throughput calibration coefficients and shall support configuring the acquisition interval (time or event count) to achieve the required statistical uncertainty.
    - Project : <ins>ctapipe</ins>
    - Status : **closed**
    - Test statement : bla bla bla

3) **From DPPS Level B Requirements Specification_stamped.pdf: 9.8.28 CTAO-B_DPPS-435 - Plate-Scale Calibrations.**
The DPPS shall be able to estimate and apply corrections for biases introduced by optical aberrations in the mapping from camera coordinates to incidence angle, using full geometry ray-tracing. The DPPS shall produce per-telescope correction maps and report residuals after correction.
    - Project : <ins>ctapipe</ins>
    - Status : **closed**
    - Test statement : bla bla bla

4) **From DPPS Level B Requirements Specification_stamped.pdf: 9.8.33 CTAO-B_DPPS-551 - Muon-based Flat-field Monitoring.**
The DPPS shall calculate alternative flat-fielding coefficients from muon analysis and use these to monitor and improve the accuracy of the coefficients obtained with the flat-field device.
    - Project : <ins>calibpipe</ins>
    - Status : **TBD**
    - Test statement : bla bla bla

5) **From DPPS_LevelB_Requirements_Batch3_Calibration.xlsx: B-DPPS-37XX Pixel-wise charge calibration from muon analysis (same as 4))**
The DPPS shall calculate alternative flat-fielding coefficients from muon analysis and use these to monitor and improve the accuracy of the coefficients obtained with the flat-field device.
    - Project : <ins>calibpipe</ins>
    - Status : **TBD**
    - Test statement : bla bla bla

6) **From DPPS_LevelB_Requirements_Batch3_Calibration.xlsx: B-DPPS-37XX Pixel-wise time calibration from muon analysis.**
The DPPS shall calculate alternative time offset coefficients from muon analysis with an rms accuracy of better than 1 ns and use these to monitor and improve the accuracy of the coefficients obtained with the flat-field device.
    - Project : <ins>calibpipe</ins>
    - Status : **TBD**
    - Test statement : bla bla bla

7) **From DPPS_LevelB_Requirements_Batch3_Calibration.xlsx: B-DPPS-37XX Optical PSF monitoring from muon analysis.**
The DPPS shall calculate alternative estimates of the optical PSF of each telescope from muon analysis and use these to monitor and improve the accuracy of the monitored optical PSF.
    - Project : <ins>calibpipe</ins>
    - Status : **closed**
    - Test statement : bla bla bla

8) **From DPPS_LevelB_Requirements_Batch3_Calibration.xlsx:  B-DPPS-37XX Degradation of individual mirrors from muon analysis.**
The DPPS shall calculate alternative estimates of the relative reflectance of each mirror with respect to the telescope average from muon analysis.
    - Project : <ins>calibpipe</ins> or <ins>ctapipe</ins> 
    - Status : **TBD**
    - Test statement : bla bla bla

9) **From DPPS_LevelB_Requirements_Batch3_Calibration.xlsx:  B-DPPS-37XX Un-biased pulse integration and noise removal for muon analysis.**
The DPPS shall make sure that biases introduced by pulse integration and noise removal to the muon analysis shall be smaller than 1% of the estimated ring image size.
    - Project : <ins>calibpipe</ins>
    - Status : **To clarify**
    - Test statement : bla bla bla

10) **From DPPS_LevelB_Requirements_Batch3_Calibration.xlsx: B-DPPS-37XX Removal of non-active pixels from the signal predictor.**
The DPPS shall exclude broken or masked pixels from the signal predictor of the muon image that is used to calculate the muon bandwidth.
    - Project : <ins>calibpipe</ins> or <ins>ctapipe</ins> 
    - Status : **TBD**
    - Test statement : bla bla bla

11) **From DPPS_LevelB_Requirements_Batch3_Calibration.xlsx: B-DPPS-37XX Correction for non-active pixels for muon analysis (deprecated and replaced with 10)**
The DPPS shall be capable of taking into account non-active (broken) pixels in the muon analysis and its impact shall account for less than 0.5% of the muon image size on average for a given Telescope.
    - Project : <ins>calibpipe</ins> or <ins>ctapipe</ins> 
    - Status : **TBD**  (deprecated and replaced with 10)
    - Test statement : bla bla bla

12) **From DPPS_LevelB_Requirements_Batch3_Calibration.xlsx: B-DPPS-37XX Non-spherical reflectors for muon analysis.**
The DPPS shall use non-circularity of the reflectors from muon analysis following the prescriptions outlined in Section 3.4.2 ("Interpolation of Flat Mirror Distance")  [RD].
    - Project : <ins>ctapipe</ins> 
    - Status : **TBD in progress**
    - Test statement : bla bla bla

13) **From DPPS_LevelB_Requirements_Batch3_Calibration.xlsx: B-DPPS-37XX Plate-scale calibrations for muon analysis (same as 3).** 
The DPPS shall be capable to estimate and correct for biases due to optical aberrations in the correspondence of camera coordinates to incidence angles, for the muon analysis.
    - Project : <ins>ctapipe</ins>
    - Status : **closed** (same as 3)
    - Test statement : bla bla bla

14) **From DPPS_LevelB_Requirements_Batch3_Calibration.xlsx: B-DPPS-37XX Finite camera focus for muon analysis.**
The DPPS shall be capable to estimate and correct for the bias on the reconstructed Cherenkov angle due to the effect of finite camera focuses for the  muon analysis using Eq. 45 of [RD].
    - Project : <ins>ctapipe</ins>
    - Status : **TBD**
    - Test statement : bla bla bla

15)  **From DPPS_LevelB_Requirements_Batch3_Calibration.xlsx: B-DPPS-37XX Geomagnetic field effects for muon analysis.**
The DPPS shall be capable of taking into account the effect of bending of the muon trajectory due to geomagnetic field effects, and to ensure that their effects bias the estimated optical throughput from muon analysis by less than 1% rms in relative terms using Eqs. 49-51 of [RD].
    - Project : <ins>ctapipe</ins>
    - Status : **TBD**
    - Test statement : bla bla bla

16)   **From DPPS_LevelB_Requirements_Batch3_Calibration.xlsx:  B-DPPS-37XX Shadow awareness for muon analysis.**
Impact distance reconstruction of the muon analysis shall include the effect of shadows from the camera and the central hole in the main reflector and the possible secondary mirror plus protecting baffles and particularly its dependency on the muon inclination.
    - Project : <ins>ctapipe</ins>
    - Status : **TBD**
    - Test statement : bla bla bla

17) **From DPPS_LevelB_Requirements_Batch3_Calibration.xlsx:  B-DPPS-37XX Secondary mirror awareness for muon analysis.**
Impact distance reconstruction of the muon analysis shall include the effect of a secondary mirror.
    - Project : <ins>ctapipe</ins>
    - Status : **TBD**
    - Test statement : bla bla bla

18) **From DPPS_LevelB_Requirements_Batch3_Calibration.xlsx:  B-DPPS-37XX Muon simulations.**
The muon analysis shall be calibrated at during commissioning of each new telescope against dedicated muon simulations, which shall correctly include all shadowing parts of the telescope, at their respective distances to the reflector. The residual rms systematic error of the simulated muon ring image pixel-wise sizes shall not exceed 1% of the one corresponding to the designed telescope.
    - Project : <ins>ctalibpipe-Snippets</ins> 
    - Status : **closed**
    - Test statement : bla bla bla

19)  **From DPPS_LevelB_Requirements_Batch3_Calibration.xlsx:  B-DPPS-37XX Extinction of muon Cherenkov light by aerosols in the air.**
The DPPS shall be capable to estimate and correct extinction of the muon Cherenkov light by aerosols in the air.
    - Project : <ins>ctalibpipe</ins> 
    - Status : **TBD**
    - Test statement : bla bla bla

20) **From DPPS_LevelB_Requirements_Batch3_Calibration.xlsx:  B-DPPS-37XX Incidence-angle dependencies of telescope camera for muon analysis.**
The DPPS shall be capable to include awareness of dependencies of the sensitivity of the camera to light inciding from angles onto the camera and correct for these. **()** __calibpipe__ or __ctapipe__  **(The test statement needs to be written and approved.)**
    - Project : <ins>ctalibpipe</ins> or <ins>ctapipe</ins>
    - Status : **To clarify**
    - Test statement : bla bla bla

21) **From DPPS_LevelB_Requirements_Batch3_Calibration.xlsx:  B-DPPS-37XX Mis-aligned mirrors for muon analysis.**
The DPPS shall be capable to take into account mis-aligned mirrors for muon analysis, and apply corrections for these. 
Residual contributions to the estimated optical throughput from muon analysis shall not exceed 0.5% (LST) or 1%(MST) in relative terms. This requirement does not apply to the muon analysis of SSTs.
    - Project : <ins>ctalibpipe</ins>
    - Status : **TBD**
    - Test statement : bla bla bla

22) **Optimize the computation by using photon energy instead of wavelength.**
This is related to the fact that Cherenkov light has a photon energy distribution that is flat with respect to wavelength (~1/lambda^2).
    - Project : <ins>ctapipe</ins>
    - Status : **TBD**
    - Test statement : bla bla bla
