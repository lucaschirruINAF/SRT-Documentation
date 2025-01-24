.. toctree::

Introduction
============

The Sardinia Radio Telescope (`SRT <http://www.srt.inaf.it/>`_) is the result of a scientific and technical project carried out by the Italian National Institute for Astrophysics (INAF), and it is managed by the Astronomical Observatory of Cagliari. It is a fully steerable multi-reflector antenna designed to operate with high efficiency across the 0.3–116 GHz frequency range. The telescope is located in the Pranu Sanguni area of San Basilio, Sardinia, Italy, about 35 km northeast of Cagliari (Latitude 39.493072° N, Longitude 9.245151° E), at about 650 m above sea level. 

Its state-of-the-art technology includes an optical design based on a quasi-Gregorian configuration with a shaped 64-m diameter primary reflector and a 7.9-m
diameter secondary reflector, in order to minimize the spillover and the standing wave between secondary mirror and feed. Moreover, the telescope is equipped with a beam wave guide (BWG) room, where there are available four 2.9-m mirrors and one 3.9-m mirror, for a total of four additional focal positions. This complex optical design permits the telescope to accomodate up to 20 receivers.
One of the most important properties of SRT is the active surface system, which allows compensation for the gravitational deformation, thermal gradients, and wind pressure on the 64-meter dish (through an electro-mechanical control), guaranteeing high antenna efficiency at high frequencies.

The official inauguration of SRT took place in September 2013. Following a six-month Early Science Program (ESP) carried out in 2016 and a refurbishment of its active surface, the telescope has been open for scientific observations to the international community since December 2018. In these years, SRT has allowed astronomical observations up to 26.5 GHz, thanks to 4 radio receivers: the dual-band L-P receiver (300-410 MHz and 1300-1800 MHz), the C-high band receiver (5.7-7.7 GHz) and the 7-beam K-band receiver (18-26.5 GHz). In 2023, a new C-low receiver (4.2-5.6 GHz) has been installed. 

Currently, a total of eight receivers are installed on SRT, covering the entire frequency range from 300 MHz to 116 GHz. The majority of them, such as the 16-beam Caruso receiver (70-116 GHz), the 19-beam Q-band receiver (33-50 GHz), Mistral (77-103 GHz) and the Tri-band receiver (18-26 GHz, 34-50 GHz and 80-116 GHz) are still in the commissioning phase, as they arrive thanks to the Italian National Operational Program (PON) funding. This project has been allocated to INAF by the Italian Ministry of University and Research (MIUR) with the aim of installing four new hig-frequency receivers on the telescope (`Govoni et al., URSI GASS 2021, Rome, Italy <https://ieeexplore.ieee.org/document/9560570>`_). These receivers will extend the operational frequency to new high frequencies (up to 116 GHz) not yet covered by SRT. During the PON-related works, the dual-band L-P receiver underwent an upgrade and is not yet available. In addition, two new receivers are currently under design and development: a C-band (4-8 GHz) phased array feed (PAF) and an S-band receiver (3–4.5 GHz).

The available receivers for the current call for proposals are: the C-low receiver, the C-high or M-band receiver and the 7-beam K-band receiver. Further details for all receivers of SRT are reported in the "Receivers" section.  

SRT offers several digital backends for data storage and processing purposes, such as Total Power, SARDARA, SKARAB, DFB, DBBC2 and DBBC3. Further details for all backends of SRT are reported in the "Backends" section.

The control software produced for SRT is named DISCOS, a distributed system based on ALMA Common Software (ACS), commanding all the devices of the telescope and allowing the user to perform radio astronomy observations. Specific details are available at the following link: `Observing with SRT <https://srt-procedures.readthedocs.io/en/latest/index.html>`_.

The telescope can be operated in single-dish or Very Long Baseline Interferometry (VLBI) mode for radio astronomy, geodynamical studies or space science. Its geographical location allows it to observe at declinations above -33 degrees.

The Astronomical Observatory of Cagliari has a mobile laboratory useful for detecting radio frequency interference (RFI) in the area surrounding the SRT. The system is described in this paper: `Bolli et al., IEEE Antennas Propag. Mag., vol. 55, pp. 19-24 (2013) <https://ieeexplore.ieee.org/document/6735468>`_. Characterizing the RFI sources and assessing their frequency band occupation are essential for understanding the impact of RFI on scientific observations. A real-time monitoring system for RFI is being developed to provide added value to astronomers during scientific observations.

A detailed description of SRT, including technical commissioning information and first light results, can be found in the technical commissioning paper:
`Bolli et. al, Journal of Astronomical Instrumentation, Vol. 4, Nos. 3 & 4 (2015) 1550008 <https://www.worldscientific.com/doi/abs/10.1142/S2251171715500087>`_.

Scientific tests and applications for the SRT are described in the following scientific validation paper:
`Prandoni et. al, A&A 608, A40 (2017) <https://www.aanda.org/articles/aa/abs/2017/12/aa30243-16/aa30243-16.html>`_.

Science done with SRT during its early-science run (2016) with the various hardware and software described below can be found here: `Science with SRT <http://www.srt.inaf.it/astronomers/science_srt/>`_. 

In the following sections, useful information for observing with the SRT in the current `Call for Proposals <https://www.radiotelescopes.inaf.it/>`_ are outlined.  


Technical features of the telescope 
===================================

The Sardinia Radio Telescope (SRT) consists of a quasi-Gregorian system that can operate in a frequency range between 300 MHz and 116 GHz, with a radiation efficiency of up to 60 percent. Its optical design comprises a quasi-parabolic 64-m main mirror (M1) and a quasi-elliptical 7.9-m subreflector (M2), offering two focal positions (i.e., the primary F1 and the Gregorian or secondary F2 focal points). Additionally, the telescope is equipped with a beam waveguide (BWG) room, which includes one 3.9-m mirror (M3) and two 2.9-m mirrors (M4 & M5), for a total of four additional focal positions (i.e., F3 & F4 and F5 & F6). The focal length to diameter ratio (f/D) and the frequency range of each focal point are listed in the following table. In this table, mechanical, logistical, and technical characteristics are also listed.


.. list-table::
   :widths: 10 20

   * - **Position**
     - Pranu Sanguni, San Basilio, Sardinia
   * - **Geodetic Coordinates (WGS84)** 
     - Latitude 39° 29' 34.93742" N;  Longitude 9° 14' 42.5764" E 
   * - **Frequency coverage**
     - 0.3 - 116 GHz
   * - **Optical configuration and frequency range**
     - Primary focus (0.3-20 GHz), Gregorian focus (7.5-116 GHz), beam wave guide (1.4-35 GHz)
   * - **Primary quasi-parabolic mirror (M1) diameter**
     - 64 m
   * - **Quasi-elliptical subreflector (M2) diameter**
     - 7.9 m
   * - **Beam wave guide mirrors (M3, M4 and M5)**
     - M3 of 3.9 m; M4&M5 of 2.9 m. 
   * - **Focal positions**
     - F1 (primary focus); F2 (Gregorian focus); F3&F4 and F5&F6 (BWG).
   * - **Focal length to diameter ratio (f/D)**
     - f1/D = 0.33; f2/D = 2.34; f3&f5/D = 1.38; f4&f6/D = 2.81
   * - **Azimuth range**
     - -90 to 450 degrees
   * - **Elevation range**
     - 5 to 90 degrees
   * - **Maximum slew rate**
     - 0.85 degrees/s in azimuth; 0.5 degrees/s in elevation
   * - **Primary surface accuracy**
     - 300 μm rms
   * - **Pointing accuracy (rms)**
     - 2 - 5"

It is worth noting that while the elevation limits range from 5 to 90 degrees, observations should ideally be planned for an elevation between 6 and 82 degrees. Only in exceptional cases should observations fall below 6 degrees or exceed 82 degrees.
One of the most important features of the Sardinia Radio Telescope (SRT) is its active surface system for the primary mirror, M1. Comprising 1008 aluminum panels and 1116 electromechanical actuators, this primary reflector compensates for gravitational deformation in quasi-real-time and undergoes continuous adjustments during observations. The actuators also facilitate the conversion of the primary mirror's shaped surface to the ideal parabolic profile during primary focus observations. The active primary reflector panels are aligned to a surface accuracy of approximately 300 μm root mean square (RMS). Further details about the active surface of SRT are reported in the following paper: 
`Bolli et al., IEEE Antennas Wirel. Propag. Lett., vol. 13, pp. 1713-1716 (2014) <https://ieeexplore.ieee.org/document/6880807>`_.

Consequently, during astronomical observations, the observer can choose among three configurations:

* shaped surface in tracking mode (it adjusts according to the observed elevation position);
* ideal parabolic profile in fixed position (optimized for an elevation of 45 degrees);
* ideal parabolic profile in tracking mode (it adjusts according to the observed elevation position).

The shaped configuration is used for receivers in the Gregorian (7.5-116 GHz) and BWG (1.4-35 GHz) foci, while the ideal parabolic configurations are used for receivers of the primary focus (0.3-20 GHz).


Cryogenic receivers of SRT
===========================

All radio receivers of SRT are cryogenically-cooled systems that operate at temperatures below 20 K. In this way, the thermal noise introduced by the receiver itself (Trec) is reduced, consequently decreasing the overall system noise temperature (Tsys), allowing for greater sensitivity in detecting weak signals from space. As mentioned in the Introduction section, 8 receivers are installed on SRT, but only 3 of them are available for the current call for proposals. In the following sections, a brief description of all SRT receivers is reported.

Receivers available for the current Call for Proposals
-------------------------------------------------------

The available receivers for the current Call for Proposals are summarized in the following table, indicating the receiver name, frequency band, number of beams, type of polarization (linear or circular), focal position, system temperature, beam size, maximum gain, and available backends. Each receiver is available in both single-dish and VLBI modes.

================== ================ ============ =========  =============== ================= ================= ============ =============================================== 
Receiver           Frequency [GHz]  Beams x Pol. Pol. type  Focal Position  Tsys @ El=45° [K] Beamsize [arcmin] Gain [K/Jy]   Available backends
================== ================ ============ =========  =============== ================= ================= ============ =============================================== 
C-low              4.2 - 5.6        1 x 2        LHCP/RHCP  Gregorian       30                3.9 @4.8GHz       0.62         TP,DFB,DBBC,SARDARA,SKARAB
C-high or M-band   5.7 - 7.7        1 x 2        LHCP/RHCP  Beam Wave Guide 32                2.7 @6.7GHz       0.69         TP,DFB,DBBC,SARDARA,SKARAB
K-band             18 - 26.5        7 x 2        LHCP/RHCP  Gregorian       60                0.8 @20.4GHz      0.62         TP(MB),DFB,DBBC,SARDARA(MB),SKARAB(MB) 
================== ================ ============ =========  =============== ================= ================= ============ =============================================== 

(MB) means that the Multi-Beam option is available for observations in K-band with the TP, SARDARA and SKARAB backends. 
The full width half maximum (FWHM) beam size, as a function of the frequency f, can be approximated by the following rule: FWHM(arcmin)=19.7/ f(GHz).

SRT receiver changes are quick, allowing for an efficient frequency agility. The selected receiver is set in its focal position within at most a few minutes.
Below is a brief description of each receiver available for this Call for Proposals, highlighting its main features.

* **C-low receiver**: It is a single-feed cryogenic system that allows the processing of signals in circular polarization (i.e. LHCP and RHCP) within the frequency range from 4.2 to 5.6 GHz. This receiver is installed on the Gregorian focus of SRT and requires the shaped configuration. To analyze the entire frequency band ranging from 4.2 to 5.6 GHz and shift it down to baseband, the local oscillator must be set to 4.2 GHz. However, due to a presence of strong RFI at the end of the band, it is possible to set the local oscillator at 4.6 GHz and a bandwidth of 300 MHz (available on DISCOS functions) to have a free-of-RFI band. A detailed description of the C-low band RFI scenario is provided in the following paper: `Schirru et. al, Sensors, 24(19), 6481 (2024) <https://doi.org/10.3390/s24196481>`_.

* **C-high or M-band receiver**: It is a single-feed cryogenic system that allows the processing of signals in circular polarization (i.e. LHCP and RHCP) within the frequency range from 5.7 to 7.7 GHz. This receiver is installed in one of the BWG focal points of SRT and requires the shaped configuration. 

* **K-band receiver**: It is a seven-feed cryogenic system that allows the processing of signals in circular polarization (i.e. LHCP and RHCP) within the frequency range from 18 to 26.5 GHz. This receiver is installed on the Gregorian focus of SRT and requires the shaped configuration. 


Receivers in the Commissioning Phase and available in the next future
-------------------------------------------------------
The receivers in the Commissioning Phase and available in the next future are summarized in the following table, indicating the receiver name, frequency band, number of beams, type of polarization (linear or circular), focal position, system temperature (estimated), beam size (estimated), maximum gain (estimated), and available backends. Each receiver will be available in both single-dish and VLBI modes.

====================== =========================== ============ ===================  =============== ======================= ================= =================== =============================================== 
Receiver               Frequency [GHz]             Beams x Pol. Pol. type            Focal Position  Tsys @ El=90° [K]       Beamsize [arcmin] Gain [k/Jy]         Available backends
====================== =========================== ============ ===================  =============== ======================= ================= =================== =============================================== 
L-P band               0.25-0.46(P); 1.3-1.8(L)    1 x 2        linear and circular  primary         50-80(P) and 25-35(L)   48(P) and 11.4(L) 0.52(P) and 0.55(L)  DFB,DBBC, SARDARA, SKARAB
Tri-band (K, Q and W)  18-26(K);34-50(Q);80-116(W) 1 x 2        LHCP/RHCP            Gregorian       -                       -                                      SARDARA, SKARAB
Q-band                 33-50                       19 x 2       LHCP/RHCP            Gregorian       -                       -                                      SARDARA (7 feed), SKARAB
Caruso (W-band)        70-116                      16 x 2       linear               Gregorian       -                       -                                      SARDARA (7 feed), SKARAB
MISTRAL                77-103                      408          -                    Gregorian       -                       -                                      Dedicated Roach 2 backend
====================== =========================== ============ ===================  =============== ======================= ================= =================== ===============================================

* **L-P band receiver**: it is a single-feed, dual-frequency receiver installed at the primary focus of the telescope, and therefore requires the parabolic configuration. It allows for simultaneous observations at L and P bands. The polarization type is linear but is also transformed to circular (LHCP and RHCP) thanks to a hybrid converter. Unfortunately, this receiver operates in a frequency range that is heavily affected by the presence of RFI from both the surrounding area and self-produced by the telescope's electronic components. The RFI level needs to be minimized. A Gregorian cover, which limits self-produced RFI at L and P bands, is always set during observation. In orther to mitigate the presence of RFI, different radio frequency filters are available for the LP-band receiver. More details on the most up-to-date frequency bands of these filters are given in the following paper: `Schirru et. al, Universe (2023), vol. 9(9), 390; <https://doi.org/10.3390/universe9090390>`_.

* **Tri-band (K, Q and W) receiver**: It is a simultaneous microwave compact Triple-Band receiving system to be installed on the three Italian radio telescopes (SRT, Medicina and Noto). The three cryogenic microwave receivers will operate simultaneously in the K / Q / W Bands (18 – 26 GHz, 34 – 50 GHz, 80 – 116 GHz). Having the same type of receiver in the three Italian antennas will allow us to strengthen the role of SRT in both the Italian and European VLBI networks. This receiver is installed on the Gregorian focus of SRT and requires the shaped configuration. Further details about this receiver are provided in the following paper: `Bolli et al., URSI GASS 2023, Sapporo, Japan <https://ieeexplore.ieee.org/document/10265655>`_.

* **Q-band receiver**: It is a 19-beam cryogenic receiver operating in the 33 – 50 GHz frequency band (Q Band) for SRT, composed of 19 double circular polarization beams. This receiver is ideal for surveying large areas of the sky in radio continuum emission and in broadband spectro-polarimetry. This receiver is installed on the Gregorian focus of SRT and requires the shaped configuration.

* **Caruso (W-band) receiver**: It is a 16-beam cryogenic receiver operating in the 70 – 116 GHz frequency band (W Band) for SRT, composed of 16 double linear polarization beams. This receiver is fundamental for the detection of complex organic molecules through polarimetric studies of galactic and extragalactic sources. This receiver is installed on the Gregorian focus of SRT and requires the shaped configuration. Further details about this receiver are provided in the following paper: `Navarrini et al., IEEE Access, vol. 10, pp. 26369-26403 (2022) <https://ieeexplore.ieee.org/document/9718287>`_.

* **MISTRAL receiver**: It is a bolometric millimetre camera for SRT operating in the 77 – 103 GHz frequency band composed of an array of 408 detectors (pixels) that simultaneously sample a wide field of view. This will be suitable for the observation of extensive and diffused emission with low surface brightness. This receiver is installed on the Gregorian focus of SRT and requires the shaped configuration. Further details about this receiver are provided in the following paper: `Paiella et al., Journal of Low Temperature Physics, vol. 217, pp 436–445 (2024) <https://doi.org/10.1007/s10909-024-03210-1>`_.

**Future receivers**: the SRT was designed to accomodate up to 20 receivers. A 7-feed S-band receiver (3 -- 4.5 GHz) is undergoing testing and designed to be placed at the primary focus of the telescope (requiring the parabolic configuration). The full commissioning of this receiver is expected to end in 2026.   


Backends 
========

The frontend (receiver) outputs are connected to the backend instruments either by coaxial cables or optical fibers, depending on whether the backend is located in the main building or below the dish. The following backends, designed for specific scientific activities, are available at the SRT site. These backends are available for both the current Call for Proposals and the Commissioning Phase:

=============== ========== ========================================================== =============== ===================== ======================================================================  
Backend         Receivers  Effective Bandwidth (MHz)                                           Sampling time   Max freq. bins        Observing modes                                  
=============== ========== ========================================================== =============== ===================== ====================================================================== 
**Total Power**   all      250,680,1200,2000                                          1-1000 ms          1                  continuum (analog)
**SARDARA**       all      300, 1200                                                  down to 5ms       1024 or 16384       spectro-polarimeter(*)    
**SARDARA**        L-P     1000 (L) - 500 (P)                                         down to 5ms       1024 or 16384       spectro-polarimeter(*)    
**DFB3**         all       256,512,1024                                               100 microsec      8192, pulsars: 2048  online pulsar folding + pulsar/transient search 
**DBBC**        all        512                                                        -                -                     VLBI 
**SKARAB**      all        1400                                                       down to 1 ms    32768                 spectro-polarimeter 
**SKARAB**      all        187.5,160,128,93.75,80,64,46.875,40,32,23.4375,20,16       down to 1 ms    65536                 spectro-polarimeter
=============== ========== ========================================================== =============== ===================== ====================================================================== 

For the Total Power and SARDARA, the backend configuration with DISCOS has different bandwidths from effective ones. For SARDARA, note that the actual available effective bandwidth of 1200 MHz corresponds to 1500 MHz in the backend setting. Similarly, for the effective bandwidth of 300 MHz, a bandwitdh of 420 MHz in the backend configuration is necessary. In the case of the Total Power, the four effective bandwidths correspond to 300, 730, 1250 or 2000 MHz, respectively. 

Total Power 
-----------

The Total Power backend is a single-band, seven-beam backend for continuum observations. Located just below the dish, this backend is formed by 14 voltage-to-frequency converters that digitize the incoming RF signals. Different IF inputs can be selected from three focal points. Different bandwidths (maximum bandwidth: 0.1 - 2.1 GHz) and attenuation levels can be selected.

This backend consists of 14 sections. Each section processes a single IF channel with a single polarization, as input. The signal is detected by a broadband square-law detector and then digitized by an A/D converter. The nominal IF band is 2 GHz (0.1-2.1 GHz). On-board filters can restrict the band to 250, 680, or 1200 MHz. The same boards also perform the focus selection for the SARDARA backend. Here are the possible configurations of the Total Power backend for different receivers:

======== ======== ====================== ==================
Receiver Sections Filters (MHz)          Sampling time (ms)
======== ======== ====================== ==================
K-band     14     250,680,1200,2000      1 -- 1000
C-high      2     250,680,1200,2000      1 -- 1000
C-low      2      250,680,1200,2000       1 -- 1000
======== ======== ====================== ==================


Digital Base Band Converter (DBBC)
----------------------------------

This digital platform is based on a flexible architecture composed of four ADC boards, with 1 GHz of bandwidth each and four Xilinx FPGA boards for data processing. The platform is designed mainly for VLBI experiments; however, a wideband spectrometer has been developed for other purposes.

Digital Filter Bank mark 3 (DFB3)
-----------------------------------------

This is an FX correlator developed by the Australia Telescope National Facility (ATNF) that performs full-Stokes observations. It allows for four inputs, each with a 1024 MHz maximum bandwidth and 8-bit sampling for a high dynamic range. The DFB3 is suitable for precise pulsar timing and searching. It allows for up to 8192 spectral channels in order to counter the effects of interstellar dispersion.

The available configurations for pulsar observations are the following:

========= ===== ========= ========= 
Obs type  Nbins  BW(MHz)  Nfreq  
========= ===== ========= =========  
folding   1024    1024    2048
folding   1024    1024    1024
folding   1024    1024     512
folding   1024    512     2048
folding   1024    512     1024
folding   1024    512      512
folding   512     1024    1024
folding   512     512     2048
folding   512     512     1024
folding   512     512      512
folding   512     256      512
folding   512     128     2048
folding   256     256     2048
folding   256     64      2048
folding   256     64      1024(*)
search            1024    1024
search            1024    512
search            512     1024    
search            512      512     
search            512      128
========= ===== ========= =========

(*) This configuration does not work for pulsars with periods < 1.6 ms.

* Choosing the best folding configuration depends in part on the period of the pulsar. One can find the best folding configuration for a range of folding periods `here <http://www.parkes.atnf.csiro.au/observing/utilities/pulsar_sched/configs.html>`_.

* These search mode configurations have been succesfully tested for the acquisition of total intensity data (npol=1) for sampling times down to 100 microseconds. Full stokes data can be obtained only with slow sampling times (>= 512 microsec for 1024 channels over 512 MHz of bandwidth and >=256 microsec for 512 channels). 

Further details about the DFB can be found in the ATNF `DFB manual <http://www.srt.inaf.it/media/uploads/astronomers/dfb.pdf>`_.

At the SRT, DFB observations are piloted using the SEADAS software. 

SARDARA
-------

The SARDARA backend is composed of seven fully-reconfigurable ROACH-2 boards that allow it to perform wide-band spectro-polarimetric observations. The many observing modes covered by SARDARA include: continuum, spectroscopy and spectro-polarimetry. In the future, it will also be able to perform high-time resolution for pulsars and fast transients (not currently available). Its sampling time can be set from 5ms to 1 s. It is the backend of choice for On-The-Fly (OTF) spectro-polarimetric observations.
Available configurations consist of:

* 420 MHz bandwith with 1024 or 16384 channels 
* 1500 MHz bandwidth with 1024 or 16384 channels 

SARDARA's spectral resolution and sensitivity are defined by its full 1500 MHz bandwidth. However only 1200 MHz of the full 1500 MHz bandwidth is usable, since the 1200 MHz filter of the Total Power backend's Focus Selector is being used as input to SARDARA. 

More detailed information on the SARDARA backend can be found here: `SARDARA <https://www.worldscientific.com/doi/full/10.1142/S2251171718500046>`_. 

SKARAB
------

*The use of this backend is admitted in shared-risk mode. Users are required to contact the antenna staff prior to submission, in order to assess the availability of software/hardware services for their specific needs.*

SKARAB backend is composed of ten fully-reconfigurable SKARAB (aka Roach 3) boards that allow it to perform wide-band spectro-polarimetric observations, as well as high-time resolution for pulsars and fast transients (not currently available). Its sampling time can be set from 1ms to 1 s. For pulsar applications, the sampling time can be set up to 16 microsec for pulsars search. Baseband recording is going to be available from 16 to 512 MHz. The full description of the SKARAB board is reported in `A. Melis et al. The SKARAB Board in the Framework of Single-Dish Radio Astronomy <https://www.worldscientific.com/doi/full/10.1142/S2251171724500089?srsltid=AfmBOopnWjd6olCUgtwWLE6MsVDWdBXZKRj9yycO6KIzi4ITdUGQovur>`_.

**SKARAB is offered in shared-risk mode in all of its configurations.**


Calibration
===========
Tests of characterization are periodically performed at SRT in order to check the status of the antenna, ensure a good functioning of the different components (e.g. active surface, receivers, backends, etc), and improve the observing performances at the different frequencies. In particular, the tests include measurements of pointing, focus curve, gain curve and beam shape for the different receivers. More details about previous test results are available in `SRT Performance Measurements <http://hdl.handle.net/20.500.12386/32536>`_.

Pointing model
---------------

This calibration procedure was used to calculate the pointing errors in ideal conditions, i.e. at night without sunlight. Actual conditions will most likely require new pointing measurements in order to take into account possible errors due to environmental factors. Pointing measurements before starting an observing session are highly recommended above 18 GHz.

Focus curve calibration
-----------------------

The focus curve is applied in real time. However, it is highly recommended that the observer performs a focus calibration before starting an observing session above 18 GHz. 

Gain curve calibration
----------------------

From the measured gain curves (Gain vs. Elevation pointing), one fits a 2-degree polynomial with the parameters $C_0$, $C_1$ and $C_2$ is considered:

$Gain (K/Jy) = C_2*El^2 + C_1*El + C_0$

for each receiver available for the current Call for Proposals, a summary of these optimal values are reported in the following.

* **C-low receiver**: the parameters refer to a peak gain of 0.60 K/Jy at 52.2 degrees of elevation (*LHCP channel*) and to a peak gain of 0.64 K/Jy at 51.7 degrees of elevation (*RHCP channel*).  

========== ====================== ====================== ======================
Parameter  4.7 GHz [K/Jy] - LHCP  4.7 GHz [K/Jy] - RHCP  4.7 GHz - normalized
========== ====================== ====================== ====================== 
$C_0$      0.57 ± 0.09            0.58 ± 0.1             0.920907             
$C_1$      0.0013 ± 0.0011        0.0025 ± 0.0027        0.00304114                    
$C_2$      -1.3e-5 ± 1.1e-5       -2.4e-5 ± 2.2e-5       -2.92721e-5                     
========== ====================== ====================== ======================

* **C-high or M-band receiver**: the parameters refer to a peak gain of 0.69 K/Jy at 45 degrees of elevation (*LHCP and RHCP channels*), valid since 2018 and reported in `SRT Performance Measurements <http://hdl.handle.net/20.500.12386/32536>`_.

========== ======================= 
Parameter  7.3 GHz [K/Jy]   
========== =======================
$C_0$      0.545439                
$C_1$      0.00525597              
$C_2$      -4.55697e-5
========== ======================= 

* **K-band receiver**: since 2022, with the installation of new low noise amplifiers (LNA) and using the look up table (LUT) named act_rev02.txt, the parameters refer to three different frequencies (18.6, 21.5 and 24.5 GHz) with a peak gain of approximately 0.6 K/Jy at about 57 degrees of elevation. In the following Table, the gain curve parameters are normalized.

========== ============= ================================== =================================== ===================================
Feed       Parameter     18.6 GHz                           21.5 GHz                            24.5 GHz 
========== ============= ================================== =================================== ===================================
0          $C_0$         0.5776 ± 0.0753                    0.4889 ± 0.1747                     0.384495 ± 0.174028
0          $C_1$         0.0145 ± 0.0034                    0.01876 ± 0.007202                  0.021743 ± 0.00718678
0          $C_2$         -0.0001251 ± 3.821e-5              -0.0001722 ± 7.416e-05              -0.000202376 ± 6.86749e-05
1          $C_0$         0.5577 ± 0.0758                    0.4842 ± 0.171                      0.386977 ± 0.168515
1          $C_1$         0.01551 ± 0.00328                  0.01844 ± 0.006853                  0.0219423 ± 0.00694715
1          $C_2$         -0.000136 ± 4.058e-5               -0.0001647 ± 7.252e-05              -0.000203621 ± 7.50384e-05
2          $C_0$         0.52691 ± 0.06596                  0.46 ± 0.1781                       0.407986 ± 0.166548
2          $C_1$         0.01521 ± 0.00345                  0.0177 ± 0.007422                   0.0182398 ± 0.00739156
2          $C_2$         0.000122 ± 3.636e-5                -0.000145 ± 6.492e-05               -0.000149043 ± 7.63124e-05
3          $C_0$         0.43543 ± 0.7798                   0.4254 ± 0.1878                     0.362377 ± 0.163381
3          $C_1$         0.01843 ± 0.00351                  0.01864 ± 0.006797                  0.020356 ± 0.00662008
3          $C_2$         -0.00015 ± 3.762e-5                -0.0001511 ± 6.928e-05              -0.000172251 ± 7.73011e-05
4          $C_0$         0.55539 ± 0.8107                   0.4732 ± 0.1646                     0.350534 ± 0.165615
4          $C_1$         0.01557 ± 0.00364                  0.01898 ± 0.006675                  0.0228525 ± 0.00664479
4          $C_2$         -0.000136 ± 3.592e-5               -0.0001709 ± 6.632e-05              -0.000210964 ± 6.80223e-05
5          $C_0$         0.57057 ± 0.07649                  0.4363 ± 0.1897                     0.451366 ± 0.176364
5          $C_1$         0.01603 ± 0.00359                  0.02169 ± 0.007745                  0.0215222 ± 0.00691995
5          $C_2$         -0.000149 ± 3.689e-5               -0.0002087 ± 6.992e-05              -0.000215915 ± 7.79329e-05
6          $C_0$         0.54905 ± 0.08142                  0.3653 ± 0.1502                     0.374763 ± 0.18176
6          $C_1$         0.01687 ± 0.00359                  0.02386 ± 0.007183                  0.0226379 ± 0.00680734
6          $C_2$         -0.000157 ± 3.877e-5               -0.0002242 ± 6.686e-05              -0.00021647 ± 6.80647e-05
========== ============= ================================== =================================== ===================================

Below, the gain curve parameters for each feed polarization (i.e. LHCP and RHCP) are listed in K/Jy.
 
========== ============= ============= ================================== =================================== ===================================
Feed       Polarization  Parameter     18.6 GHz [K/Jy]                    21.5 GHz [K/Jy]                     24.5 GHz [K/Jy]
========== ============= ============= ================================== =================================== ===================================
0          LHCP          $C_0$         0.29553 ± 0.04209                  0.27560 ± 0.13769                   0.23353 ± 0.14244
0          RHCP          $C_0$         0.34778 ± 0.04295                  0.31669 ± 0.15472                   0.21584 ± 0.12503
0          LHCP          $C_1$         0.00703 ± 0.00196                  0.01117 ± 0.00550                   0.01326 ± 0.00608
0          RHCP          $C_1$         0.00874 ± 0.00241                  0.01148 ± 0.00598                   0.01215 ± 0.00529
0          LHCP          $C_2$         -6.122e-5 ± 1.993e-5               -1.025e-4 ± 5.514e-5                -1.237e-4 ± 6.114e-5
0          RHCP          $C_2$         -7.528e-5 ± 2.377e-5               -1.053e-4 ± 5.606e-5                -1.129e-4 ± 5.061e-5
========== ============= ============= ================================== =================================== ===================================

========== ============= ============= ================================== =================================== ===================================
Feed       Polarization  Parameter     18.6 GHz [K/Jy]                    21.5 GHz [K/Jy]                     24.5 GHz [K/Jy]
========== ============= ============= ================================== =================================== ===================================
1          LHCP          $C_0$         0.27615 ± 0.04171                  0.295073 ± 0.148809                 0.204488 ± 0.1225
1          RHCP          $C_0$         0.31550 ± 0.04706                  0.286016 ± 0.135291                 0.212531 ± 0.122012
1          LHCP          $C_1$         0.00757 ± 0.00182                  0.0109447 ± 0.00518332              0.0119961 ± 0.00510499
1          RHCP          $C_1$         0.00876 ± 0.00202                  0.0111679 ± 0.00568998              0.011639 ± 0.00480572
1          LHCP          $C_2$         -6.523e-5 ± 1.986e-5               -9.79487e-05 ± 5.49052e-05          -0.000111456 ± 5.51174e-05
1          RHCP          $C_2$         -7.689e-5 ± 2.355e-5               -9.96425e-05 ± 5.43285e-05          -0.000107878 ± 5.43345e-05
========== ============= ============= ================================== =================================== ===================================

========== ============= ============= ================================== =================================== ===================================
Feed       Polarization  Parameter     18.6 GHz [K/Jy]                    21.5 GHz [K/Jy]                     24.5 GHz [K/Jy]
========== ============= ============= ================================== =================================== ===================================
2          LHCP          $C_0$         0.20375 ± 0.02940                  0.292589 ± 0.147449                 0.210224 ± 0.114295
2          RHCP          $C_0$         0.22625 ± 0.03680                  0.336209 ± 0.1585                   0.206251 ± 0.113139
2          LHCP          $C_1$         0.00618 ± 0.00134                  0.0118605 ± 0.00570499              0.00921301 ± 0.00456637
2          RHCP          $C_1$         0.00653 ± 0.00155                  0.0121886 ± 0.00634103              0.00938632 ± 0.00463009
2          LHCP          $C_2$         -5.099e-5 ± 1.66e-5                -0.000108877 ± 5.89716e-05          -7.55489e-05 ± 4.95745e-05
2          RHCP          $C_2$         -5.255e-5 ± 1.683e-5               -0.000111816 ± 5.93967e-05          -7.64335e-05 ± 4.9177e-05
========== ============= ============= ================================== =================================== ===================================

========== ============= ============= ================================== =================================== ===================================
Feed       Polarization  Parameter     18.6 GHz [K/Jy]                    21.5 GHz [K/Jy]                     24.5 GHz [K/Jy]
========== ============= ============= ================================== =================================== ===================================
3          LHCP          $C_0$         0.18439 ± 0.03392                  0.246861 ± 0.125465                 0.189725 ± 0.119376
3          RHCP          $C_0$         0.21442 ± 0.03569                  0.235651 ± 0.131892                 0.216547 ± 0.129212
3          LHCP          $C_1$         0.00766 ± 0.00142                  0.0109026 ± 0.00516603              0.0113947 ± 0.00534664
3          RHCP          $C_1$         0.00908 ± 0.00163                  0.0102305 ± 0.00511277              0.0113357 ± 0.00533022
3          LHCP          $C_2$         -6.417e-5 ± 1.588e-5               -8.87174e-05 ± 4.96222e-05          -9.65221e-05 ± 5.23041e-05
3          RHCP          $C_2$         -7.413e-5 ± 1.971e-5               -8.26684e-05 ± 5.21071e-05          -9.57863e-05 ± 5.69126e-05
========== ============= ============= ================================== =================================== ===================================

========== ============= ============= ================================== =================================== ===================================
Feed       Polarization  Parameter     18.6 GHz [K/Jy]                    21.5 GHz [K/Jy]                     24.5 GHz [K/Jy]
========== ============= ============= ================================== =================================== ===================================
4          LHCP          $C_0$         0.27392 ± 0.04142                  0.288737 ± 0.133335                 0.192837 ± 0.11939
4          RHCP          $C_0$         0.23708 ± 0.03635                  0.286138 ± 0.148295                 0.191103 ± 0.126452
4          LHCP          $C_1$         0.00840 ± 0.00176                  0.0114427 ± 0.00545521              0.0126351 ± 0.00549263
4          RHCP          $C_1$         0.00666 ± 0.00150                  0.011585 ± 0.00544425               0.012386 ± 0.00483559
4          LHCP          $C_2$         -7.127e-5 ± 1.867e-5               -0.000103027 ± 5.68918e-05          -0.000116752 ± 4.97064e-05
4          RHCP          $C_2$         -5.844e-5 ± 1.492e-5               -0.000104363 ± 5.20853e-05          -0.000114232 ± 4.85808e-05
========== ============= ============= ================================== =================================== ===================================

========== ============= ============= ================================== =================================== ===================================
Feed       Polarization  Parameter     18.6 GHz [K/Jy]                    21.5 GHz [K/Jy]                     24.5 GHz [K/Jy]
========== ============= ============= ================================== =================================== ===================================
5          LHCP          $C_0$         0.23114 ± 0.02934                  0.252526 ± 0.136751                 0.253627 ± 0.138837
5          RHCP          $C_0$         0.17497 ± 0.02472                  0.254548 ± 0.138509                 0.256997 ± 0.144074
5          LHCP          $C_1$         0.00717 ± 0.00145                  0.0123979 ± 0.00517644              0.01167 ± 0.00550318
5          RHCP          $C_1$         0.00492 ± 0.00113                  0.0127905 ± 0.00587018              0.012677 ± 0.00567954
5          LHCP          $C_2$         -6.51e-5 ± 1.667e-5                -0.000119252 ± 5.212e-05            -0.000117045 ± 5.82984e-05
5          RHCP          $C_2$         -4.597e-5 ± 1.184e-5               -0.000123042 ± 5.72554e-05          -0.000127221 ± 5.4015e-05
========== ============= ============= ================================== =================================== ===================================

========== ============= ============= ================================== =================================== ===================================
Feed       Polarization  Parameter     18.6 GHz [K/Jy]                    21.5 GHz [K/Jy]                     24.5 GHz [K/Jy]
========== ============= ============= ================================== =================================== ===================================
6          LHCP          $C_0$         0.26855 ± 0.04260                  0.201308 ± 0.1297                   0.177388 ± 0.107379
6          RHCP          $C_0$         0.24769 ± 0.03564                  0.22931 ± 0.14374                   0.237505 ± 0.142491
6          LHCP          $C_1$         0.00860 ± 0.00158                  0.0138771 ± 0.00529243              0.0108469 ± 0.0044276
6          RHCP          $C_1$         0.00760 ± 0.00162                  0.014143 ± 0.00630654               0.0141759 ± 0.00615217
6          LHCP          $C_2$         -7.996e-5 ± 1.67e-5                -0.000130758 ± 5.19174e-05          -0.000103621 ± 4.42849e-05
6          RHCP          $C_2$         -7.114e-5 ± 1.759e-5               -0.000132548 ± 6.20251e-05          -0.000135688 ± 5.57525e-05
========== ============= ============= ================================== =================================== ===================================

For the observations performed unitl 2022, where the receiver was equipped with old LNAs, the gain curve parameters corresponding to the Feed 0 are listed in the following table: 

========== ================================== ================================== 
Parameter  25.5 GHz [K/Jy] until 2018 (*)     20 GHz [K/Jy] until 2022 (**)
========== ================================== ================================== 
$C_0$      0.364897                           0.131822
$C_1$      0.00624137                         0.0129284
$C_2$      -4.60020e-5                        -9.79198e-5
========== ================================== ==================================
(*) `Prandoni et al. (2017) <https://doi.org/10.1051/0004-6361/201630243>`_.

(**) `SRT Performance Measurements <http://hdl.handle.net/20.500.12386/32536>`_.



Regarding receivers in the Commissining Phase, previous values of $C_0$, $C_1$ and $C_2$ are available for the L-band receiver. Results about others receivers will be presented in the next future.

* **L-band receiver**: valid since 2015 and reported in `Bolli et al. (2015) <https://doi.org/10.1142/S2251171715500087>`_.

========== ======================== 
Parameter  Value [deg] for L-band 
========== ======================== 
$C_0$      0.5061                
$C_1$      0.002390              
$C_2$      -0.000021             
========== ======================== 


Beam shape
----------

In the following tables, the second lobe and third lobe percentages correspond to the contribution of the counts in that lobe as compared to the
central beam. 

* **C-low receiver**

===================== =============== ==============
Elevation range (deg) Second lobe (%) Third lobe (%)
===================== =============== ==============
15-25                                
25-35                  
35-50                  
50-65                  
65-75                  
75-85                  
===================== =============== ==============

* **C-high or M-band receiver**

===================== =============== ==============
Elevation range (deg) Second lobe (%) Third lobe (%)
===================== =============== ==============
15-25                 1.7             0.65
25-35                 1.7             0.42
35-50                 1.4             0.41
50-65                 1.0             0.41
65-75                 1.5             0.43
75-85                 2.0             0.40
===================== =============== ==============

* **K-band receiver**

===================== =============== ==============
Elevation range (deg) Second lobe (%) Third lobe (%)
===================== =============== ==============
20-40                 11              0.6
40-60                 4.9             0.5
60-80                 3.4             0.5
===================== =============== ==============


List of calibrators
-------------------

Here is a list of useful calibrators for various types of calibration:

========== =================== =========================
Flux       Polarization angle  Instrumental polarization
========== =================== =========================
3C286      3C286               3C84
3C147      3C138               NGC7027
3C48
3C295
========== =================== =========================

For pointing calibration, see below in "Useful links".

Derotator alignment
-------------------

The derotator has been aligned within 1-2 arcseconds.

Data quicklook
==============

Information about a data quicklook will be inserted here very soon.

Data conversion
===============

Conversion of data acquired in spectroscopic mode
-------------------------------------------------

Conversion to the GILDAS data format is provided for data acquired in Nodding and Position Switching modes with the SARDARA and XARCOS backends, including
spectra containing the signal from the noise diode (when used).

Useful links
============

A general description of the SRT, including technical commissioning information and first light results, can be found in the technical commissioning paper:
`Bolli et. al, Journal of Astronomical Instrumentation, Vol. 4, Nos. 3 & 4 (2015) 1550008 <https://www.worldscientific.com/doi/abs/10.1142/S2251171715500087>`_.

Scientific tests and applications for the SRT are described in the following scientific validation paper:
`Prandoni et. al, A&A 608, A40 (2017) <https://www.aanda.org/articles/aa/abs/2017/12/aa30243-16/aa30243-16.html>`_.

Science done with SRT during its early-science run (2016) with the various hardware and software described below can be found here: `Science with SRT <http://www.srt.inaf.it/astronomers/science_srt/>`_. 

Spectral-polarimetric techniques with SRT: `Sardinia Radio Telescope wide-band spectral-polarimetric observations of the galaxy cluster 3C 129 <https://arxiv.org/abs/1607.03636>`_.

ROACH1 backend for baseband data recording and pulsar observations: `OAC Internal Report N. 39 <http://www.oa-cagliari.inaf.it/area.php?page_id=10&skip=3>`_.  

SARDARA backend description: `SARDARA <https://www.worldscientific.com/doi/full/10.1142/S2251171718500046>`_. 

Gain curve calibration at L-band: `Orlati et al. <http://www.ira.inaf.it/Library/rapp-int/499-16.pdf>`_.

Pointing calibration: `Tarchi et al. (2013) OAC Internal Report N. 27 <http://www.oa-cagliari.inaf.it/area.php?page_id=10&skip=4>`_.

`Ricci et al., "A first extented catalogue of pointing/focus calibrators for the Sardinia Radio Telescope" <http://www.ira.inaf.it/Library/rapp-int/496-16.pdf>`_.

User guide and observing modes
==============================

Instructions for observing at the SRT with different modalities (receivers, backends, modes) are provided here: `instructions <http://srt-procedures.readthedocs.io/en/latest/>`_

A complete manual about the Italian radio antennas is found here: `DISCOS <http://discos.readthedocs.io/en/latest/index.html>`_.

Observing tools
===============

Source visibilites can be determined using the `CASTIA online tool <http://www.ira.inaf.it/Observing/castia/site/index.php>`_.

The online Exposure Time Calculator (ETC) can be found here: `ETC tool  <http://www.ira.inaf.it/expotime/all_ETC.html>`_.


