.. toctree::

Introduction
============

The Sardinia Radio Telescope (SRT) is the result of a scientific and technical project carried out by the Italian National Institute for Astrophysics (INAF), and it is managed by the Astronomical Observatory of Cagliari. It is a fully steerable multi-reflector antenna designed to operate with high efficiency across the 0.3–116 GHz frequency range. The telescope is located in the Pranu Sanguni area of San Basilio, Sardinia, Italy, about 35 km northeast of Cagliari (Latitude 39.493072° N, Longitude 9.245151° E), at about 650 m above sea level. 

Its state-of-the-art technology includes an optical design based on a quasi-Gregorian configuration with a shaped 64-m diameter primary reflector and a 7.9-m
diameter secondary reflector, in order to minimize the spillover and the standing wave between secondary mirror and feed. Moreover, the telescope is equipped with a beam wave guide (BWG) room, where there are available four 2.9-m mirrors and one 3.9-m mirror, for a total of four additional focal positions. This complex optical design permits the telescope to accomodate up to 20 receivers.
One of the most important properties of SRT is the active surface system, which allows compensation for the gravitational deformation, thermal gradients, and wind pressure on the 64-meter dish (through an electro-mechanical control), guaranteeing high antenna efficiency at high frequencies.

The official inauguration of SRT took place in September 2013. Following a six-month Early Science Program (ESP) carried out in 2016 and a refurbishment of its active surface, the telescope has been open for scientific observations to the international community since December 2018. In these years, SRT has allowed astronomical observations up to 26.5 GHz, thanks to 4 radio receivers: the dual-band L-P receiver (300-410 MHz and 1300-1800 MHz), the C-high band receiver (5.7-7.7 GHz) and the 7-beam K-band receiver (18-26.5 GHz). In 2023, a new C-low receiver (4.2-5.6 GHz) has been installed. 

Currently, a total of eight receivers are installed on SRT, covering the entire frequency range from 300 MHz to 116 GHz. The majority of them, such as the 16-beam Caruso receiver (70-116 GHz), the 19-beam Q-band receiver (33-50 GHz), Mistral (77-103 GHz) and the Tri-band receiver (18-26 GHz, 34-50 GHz and 80-116 GHz) are still in the commissioning phase, as they arrive thanks to the Italian National Operational Program (PON) funding. This project has been allocated to INAF by the Italian Ministry of University and Research (MIUR) with the aim of installing four new hig-frequency receivers on the telescope (`Govoni et al., URSI GASS 2021, Rome, Italy <https://ieeexplore.ieee.org/document/9560570>`_). These receivers will extend the operational frequency to new high frequencies (up to 116 GHz) not yet covered by SRT. During the PON-related works, the dual-band L-P receiver underwent an upgrade and is not yet available. In addition, two new receivers are currently under design and development: a C-band (4-8 GHz) phased array feed (PAF) and an S-band receiver (3–4.5 GHz).

The available receivers for the current call for proposals are: the C-low receiver, the C-high receiver and the 7-beam K-band receiver. Further details for all receivers of SRT are reported in the "Receivers" section.  

SRT offers several digital backends for data storage and processing purposes, such as Total Power, SARDARA, SKARAB, DFB, DBBC2 and DBBC3. Further details for all backends of SRT are reported in the "Backends" section.

The control software produced for SRT is named DISCOS, a distributed system based on ALMA Common Software (ACS), commanding all the devices of the telescope and allowing the user to perform radio astronomy observations. Specific details are available at the following link: `Observing with SRT <https://srt-procedures.readthedocs.io/en/latest/index.html>`_.

The telescope can be operated in single-dish or Very Long Baseline Interferometry (VLBI) mode for radio astronomy, geodynamical studies or space science. Its geographical location allows it to observe at declinations above -33 degrees.

A general description of the SRT, including technical commissioning information and first light results, can be found in the technical commissioning paper:
`Bolli et. al, Journal of Astronomical Instrumentation, Vol. 4, Nos. 3 & 4 (2015) 1550008 <https://www.worldscientific.com/doi/abs/10.1142/S2251171715500087>`_.

Scientific tests and applications for the SRT are described in the following scientific validation paper:
`Prandoni et. al, A&A 608, A40 (2017) <https://www.aanda.org/articles/aa/abs/2017/12/aa30243-16/aa30243-16.html>`_.

Science done with SRT during its early-science run (2016) with the various hardware and software described below can be found here: `Science with SRT <http://www.srt.inaf.it/astronomers/science_srt/>`_. 

In the following sections, useful information for observing with the SRT in the current call for proposals (published ------ with a deadline of -------) are outlined. We note that remote observing is not currently available for the Sardinia Radio Telescope; each proposing team will need to send at least one observer to the SRT to prepare the observing schedules and perform the observations on site. 


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
`Bolli et. al, IEEE Antennas Wirel. Propag. Lett., vol. 13, pp. 1713-1716 (2014) <https://ieeexplore.ieee.org/document/6880807>`_.

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
C-high or M-band   5.7 - 7.7        1 x 2        LHCP/RHCP  Beam Wave Guide 32                2.7 @6.7GHz       0.66         TP,DFB,DBBC,SARDARA,SKARAB
K-band             18 - 26.5        7 x 2        LHCP/RHCP  Gregorian       60                0.8 @20.4GHz      0.66         TP(MB),DFB,DBBC,SARDARA(MB),SKARAB(MB) 
================== ================ ============ =========  =============== ================= ================= ============ =============================================== 

(MB) means that the Multi-Beam option is available for observations in K-band with the TP, SARDARA and SKARAB backends. 
The full width half maximum (FWHM) beam size, as a function of the frequency f, can be approximated by the following rule: FWHM(arcmin)=19.7/ f(GHz).

SRT receiver changes are quick, allowing for an efficient frequency agility. The selected receiver is set in its focal position within at most a few minutes.
Below is a brief description of each receiver available for this Call for Proposals, highlighting its main features.

* **C-low receiver**: It is a single-feed cryogenic system that allows the processing of signals in circular polarization (i.e. LHCP and RHCP) within the frequency range from 4.2 to 5.6 GHz. This receiver is installed on the Gregorian focus of SRT and requires the shaped configuration. To analyze the entire frequency band ranging from 4.2 to 5.6 GHz and shift it down to baseband, the local oscillator must be set to 4.2 GHz. However, due to a presence of strong radio frequency interferences (RFI) at the beginning of the band, it is possible to set the local oscillator at 4.6 GHz and a bandwidth of 300 MHz (available on DISCOS functions) to have a free-of-RFI band. 

* **C-high or M-band receiver**: It is a single-feed cryogenic system that allows the processing of signals in circular polarization (i.e. LHCP and RHCP) within the frequency range from 5.7 to 7.7 GHz. This receiver is installed in one of the BWG focal points of SRT and requires the shaped configuration. 

* **K-band receiver**: It is a seven-feed cryogenic system that allows the processing of signals in circular polarization (i.e. LHCP and RHCP) within the frequency range from 18 to 26.5 GHz. This receiver is installed on the Gregorian focus of SRT and requires the shaped configuration. 


Receivers in the Commissioning Phase and available in the next future
-------------------------------------------------------
The receivers in the Commissioning Phase and available in the next future are summarized in the following table, indicating the receiver name, frequency band, number of beams, type of polarization (linear or circular), focal position, system temperature (estimated), beam size (estimated), maximum gain (estimated), and available backends. Each receiver will be available in both single-dish and VLBI modes.

====================== =========================== ============ ===================  =============== ======================= ================= =================== =============================================== 
Receiver               Frequency [GHz]             Beams x Pol. Pol. type            Focal Position  Tsys @ El=90° [K]       Beamsize [arcmin] Gain [k/Jy]         Available backends
====================== =========================== ============ ===================  =============== ======================= ================= =================== =============================================== 
L-P band               0.25-0.46(P); 1.3-1.8(L)    1 x 2        linear and circular  primary         50-80(P) and 25-35(L)   48(P) and 11.4(L) 0.52(P) and 0.55(L)  DBBC,ROACH1 (P) and DFB,DBBC,ROACH1,SARDARA (L)
Tri-band (K, Q and W)  18-26(K);34-50(Q);80-116(W) 1 x 2        LHCP/RHCP            Gregorian       -                       -                                      -
Q-band                 33-50                       19 x 2       LHCP/RHCP            Gregorian       -                       -                                      -
Caruso (W-band)        70-116                      16 x 2       linear               Gregorian       -                       -                                      -
MISTRAL                77-103                      408          -                    Gregorian       -                       -                                      -
====================== =========================== ============ ===================  =============== ======================= ================= =================== ===============================================

* **L-P band receiver**: it is a single-feed, dual-frequency receiver installed at the primary focus of the telescope, and therefore requires the parabolic configuration. It allows for simultaneous observations at L and P bands. The polarization type is linear but is also transformed to circular (LHCP and RHCP) thanks to a hybrid converter. Unfortunately, this receiver operates in a frequency range that is heavily affected by the presence of RFI from both the surrounding area and self-produced by the telescope's electronic components. The RFI level needs to be minimized. A Gregorian cover, which limits self-produced RFI at L and P bands, is always set during observation. In orther to mitigate the presence of RFI, different radio frequency filters are available for the LP-band receiver. More details on the most up-to-date frequency bands of these filters are given in the following paper: `Schirru et. al, Universe (2023), vol. 9(9), 390; <https://doi.org/10.3390/universe9090390>`_.

* **Tri-band (K, Q and W) receiver**: It is a simultaneous microwave compact Triple-Band receiving system to be installed on the three Italian radio telescopes (SRT, Medicina and Noto). The three cryogenic microwave receivers will operate simultaneously in the K / Q / W Bands (18 – 26 GHz, 34 – 50 GHz, 80 – 116 GHz). Having the same type of receiver in the three Italian antennas will allow us to strengthen the role of SRT in both the Italian and European VLBI networks. This receiver is installed on the Gregorian focus of SRT and requires the shaped configuration.

* **Q-band receiver**: It is a 19-beam cryogenic receiver operating in the 33 – 50 GHz frequency band (Q Band) for SRT, composed of 19 double circular polarization beams. This receiver is ideal for surveying large areas of the sky in radio continuum emission and in broadband spectro-polarimetry. This receiver is installed on the Gregorian focus of SRT and requires the shaped configuration.

* **Caruso (W-band) receiver**: It is a 16-beam cryogenic receiver operating in the 70 – 116 GHz frequency band (W Band) for SRT, composed of 16 double linear polarization beams. This receiver is fundamental for the detection of complex organic molecules through polarimetric studies of galactic and extragalactic sources. This receiver is installed on the Gregorian focus of SRT and requires the shaped configuration.

* **MISTRAL receiver**: It is a bolometric millimetre camera for SRT operating in the 77 – 103 GHz frequency band composed of an array of 408 detectors (pixels) that simultaneously sample a wide field of view. This will be suitable for the observation of extensive and diffused emission with low surface brightness. This receiver is installed on the Gregorian focus of SRT and requires the shaped configuration.

**Future receivers**: the SRT was designed to accomodate up to 20 receivers. A 7-feed S-band receiver (3 -- 4.5 GHz) is undergoing testing and designed to be placed at the primary focus of the telescope (requiring the parabolic configuration). The full commissioning of this receiver is expected to end in 2026.   


Backends 
========

The frontend (receiver) outputs are connected to the backend instruments either by coaxial cables or optical fibers, depending on whether the backend is located in the main building or below the dish. The following backends, designed for specific scientific activities, are available at the site:

These backends are available for the current call for proposals:

=============== ======= ======================= =============== ===================== ====================================================================== 
Backend          Bands   Bandwidth (MHz)        Sampling time   Max freq. bins        Observing modes                                  
=============== ======= ======================= =============== ===================== ====================================================================== 
**Total Power**   C,K   250,680,1200,2000       1-1000 ms          1                  continuum (analog)
**XARCOS**        C,K   0.5,2.0,7.8,62.5        10s               2048                spectro-polarimeter
**SARDARA**       C,K   420(300*),1500(1200*)     down to 5ms       1024 or 16384       spectro-polarimeter(*)    
**SARDARA**        L    420(90/100*),1500(500*)   down to 5ms       1024 or 16384       spectro-polarimeter(*)    
**DFB3**         L,C,K  256,512,1024            100 microsec      8192, pulsars: 2048  online pulsar folding + pulsar/transient search 
**ROACH1**      P,L,C,K         128             -                (varies)              baseband recorder + offline pulsar folding + pulsar/transient search
**DBBC**        P,L,C,K         512             -                -                     VLBI 
=============== ======= ======================= =============== ===================== ====================================================================== 
 
(*) For the 1500 MHz SARDARA configuration, the actual available RF bandwidth is 1200 MHz with the C-band and K-band receivers. 
Similarly, for the 420 MHz SARDARA configuration, the effective RF bandwidth is 300 MHz with the K-band and C-band receivers. Instead, the L-band receiver only has 500 MHz of RF bandwidth; when the SARDARA 420 MHz configuration is needed, the actual available RF bandwidth for SARDARA is 100 MHz (when selecting the XXL3 or XXC3 filters) or 90 MHz (when selecting the XXL5 or XXC5 filters).

Total Power 
-----------

The Total Power backend is a single-band, seven-beam backend for continuum observations. Located just below the dish, this backend is formed by 14 voltage-to-frequency converters that digitize the incoming RF signals. Different IF inputs can be selected from three focal points. Different bandwidths (maximum bandwidth: 0.1 - 2.1 GHz) and attenuation levels can be selected.

This backend consists of 14 sections. Each section processes a single IF channel with a single polarization, as input. The signal is detected by a broadband square-law detector and then digitized by an A/D converter. The nominal IF band is 2 GHz (0.1-2.1 GHz). On-board filters can restrict the band to 250, 680, or 1200 MHz. The same boards also perform the focus selection for the SARDARA backend. Here are the possible configurations of the Total Power backend for different receivers:

======== ======== ====================== ==================
Receiver Sections Filters (MHz)          Sampling time (ms)
======== ======== ====================== ==================
K-band     14     250,680,1200,2000      1 -- 1000
C-band      2     250,680,1200,2000      1 -- 1000
======== ======== ====================== ==================

XARCOS
------

This is a seven-beam, narrow-band, digital spectro-polarimeter with 8x2 input channels. The working bandwidth is 135-240 MHz and the maximum number of spectral channels is 2x2048 per polarization and per output channel. The instantaneous bandwidth ranges between 0.488 and 62.5 MHz and the maximum effective spectral resolution is ~500 Hz.

XARCOS is a spectro-polarimeter with a maximum bandwidth of 62.5 MHz capable of processing up to 16 IFs, thus fitting the seven-feed dual polarization K-band receiver array SRT is equipped with. Because its dump time is set to 10 seconds, it is not suitable for On-The-Fly (OTF) observations. 
The observer can select the following configurations:

* XK77, to use the full K-band array; each digital sample has a 6-bit range. Full-Stokes sections are recorded, each having a 62.5MHz bandwidth and 2048(x4) channels.
* XK03, to use the K-band feeds #0 and #3. Each feed outputs two full Stokes sections respectively having bandwidths of 62.5 MHz and 4 MHz and 2048(x4) channels. Each digital sample has an 8-bit range.
* XK06, to use the K-band feeds #0 and #6. Each feed outputs two full Stokes sections respectively having bandwidths of 62.5 MHz and 4 MHz and 2048(x4) channels. Each digital sample has an 8-bit range.
* XK00, to use only the K-band central feed. It outputs four full-Stokes sections respectively with bandwidths of 62.5 MHz, 8 MHz, 2 MHz and 0.5 MHz, each having 2048(x4) channels. Each digital sample has an 8-bit range.
* XC00 , to use the C-band receiver. It outputs four full-Stokes sections respectively with bandwidths of 62.5 MHz, 8 MHz, 2 MHz and 0.5 MHz.

More information about XARCOS configurations can be found here: 
`Melis et al., OAC Internal report N. 52 <http://www.oa-cagliari.inaf.it/download.php?id_file=YQ9rg6JYb9mniCarnPrkZ6SZIvrwI1S%2FVGL58uBsIkX36r28s%2FDbSXyE0smKJiWa5FCsB7mRWR5SOZaxg83MVg%3D%3D>`_.

It is worth noting that, given a particular configuration (e.g. XK00), the sections are obtained simultaneously. For each section, the bandwidth and
starting frequency can then be set. For more information about this procedure, see `XARCOS <https://discos.readthedocs.io/en/latest/user/srt/source/Backend.html#xarcos>`_.

Notes:

* XARCOS has been tested in circular polarization. Linear polarization observations are also admitted but in shared-risk mode. The full-Stokes configuration is therefore in shared-risk mode. Please contact the antenna staff.

* At C-band, standing waves have been identified that affect observations for Tcontinuum/Tsys > 0.05 (value to be confirmed). 


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

ROACH1
------

*The use of this backend is admitted in shared-risk mode. Users are required to contact the antenna staff prior to submission, in order to assess the availability of software/hardware services for their specific needs.*

The ROACH1 (or ROACH) backend is an FPGA board developed by the CASPER collaboration, with two ADC converters and a reprogrammable architecture. It can be used to acquire **baseband data** (voltages) or for **real-time folding of pulsar data**, thanks to the PSRDADA software. The currently available bandwidth is 128 MHz using a CPU cluster with 8 nodes (each node processes 16 MHz, so 8 x 16 MHz in total).

The ROACH1 backend has been the backend of choice for the Large European Array for Pulsars (LEAP) project. More information on the implementation of the LEAP project with the ROACH1 backend can be found here: `OAC Internal Report N. 39 <http://www.oa-cagliari.inaf.it/area.php?page_id=10&skip=3>`_. It is also used to perform all P-band pulsar observations at SRT. Its ability to perform coherent de-dispersion makes it a superior backend compared to the DFB. Its 128 MHz of available bandwidth (only 128 MHz of its 512 MHz capability is currently available because of the limited number of installed CPU nodes) is largely sufficient for P-band but more limited for L-band. In the near future, access to 
GPU nodes will increase the available bandwidth to 512 MHz. 

Note: for the current call for proposals, no real-time folding of data will be performed for pulsar observations with this backend. The data will be acquired in baseband mode and folded offline during the data post-processing. The final data output will be made available by antenna staff after a few hours or days.  

SARDARA
-------

*The use of this backend is admitted in shared-risk mode. Users are required to contact the antenna staff prior to submission, in order to assess the availability of software/hardware services for their specific needs.*

The SARDARA backend is composed of seven fully-reconfigurable ROACH-2 boards that allow it to perform wide-band spectro-polarimetric observations. The many observing modes covered by SARDARA include: continuum, spectroscopy and spectro-polarimetry. In the future, it will also be able to perform high-time resolution for pulsars and fast transients (not currently available). Its sampling time can be set from 5ms to 1 s. It is the backend of choice for On-The-Fly (OTF) spectro-polarimetric observations.
Available configurations consist of:

**in C and K bands:**

* 420 MHz bandwith with 1024 or 16384 channels 
* 1500 MHz bandwidth with 1024 or 16384 channels 

SARDARA's spectral resolution and sensitivity are defined by its full 1500 MHz bandwidth. However only 1200 MHz of the full 1500 MHz bandwidth is usable, since the 1200 MHz filter of the Total Power backend's Focus Selector is being used as input to SARDARA. 

**L-band setup**

The full bandwidth for this receiver is 500 MHz (1.3-1.8 GHz). RF filters must be used (choose between XXL4, XXL2 etc.). For the 420 MHz configuration, the available filters are: XXL3, XXL5, XXC3 and XXC5 (to be selected following the needed sky frequency and polarization). We note that with these filters, the effective RF bandwidth is 100 MHz (using the XXL3 or XXC3 filters) or 90 MHz (using the XXL5 or XXC5 filters). 

**SARDARA is offered in shared-risk mode in all of its configurations.**

More detailed information on the SARDARA backend can be found here: `SARDARA <https://www.worldscientific.com/doi/full/10.1142/S2251171718500046>`_. 

Calibration
===========

Pointing model
---------------

This calibration procedure was used to calculate the pointing errors in ideal conditions, i.e. at night without sunlight. Actual conditions will most likely require new pointing measurements in order to take into account possible errors due to environmental factors. Pointing measurements before starting an observing session are highly recommended and can be included in the observation schedule.

In the table below, we report the calculated rms values in ideal conditions:

========== ======================== ====================== ======================= ======================
Parameter  Value [deg] for L-band** Value [deg] for C-low  Value [deg] for C-high  Value [deg] for K-band
========== ======================== ====================== ======================= ======================
Az-mean                                                        +0.000440               +0.000850
Az-rms       +0.001944(*)                                      +0.000790               +0.000870
El-mean                                                        -0.001660               -0.001280
El-rms       +0.001944(*)                                      +0.000910               +0.001200
========== ======================== ====================== ======================= ======================

(**) As noticed above, the L-band receiver is in the commissioning phase.

(*) values for L-band from Bolli et al (2015)

Focus curve calibration
-----------------------

The focus curve is applied in real time. However, it is highly recommended that for C-low, C-high (M-band) and K-band observations, the observer performs a focus calibration before starting an observing session. Since a high presence of unwanted signals (i.e. radio frequency interference or RFI) has been noted at the beginning of the C-low band (at about 4.2 GHz), the local oscillator frequency can be adjusted to avoid backend saturation. A recommended example value for this local oscillator frequency is 4.6 GHz with a bandwidth of 300 MHz.

Gain curve calibration
----------------------

From the measured gain curves (Gain vs. Elevation pointing), one fits a 2-degree polynomial with the parameters $C_0$, $C_1$ and $C_2$ is considered:

$Gain (K/Jy) = C_2*El^2 + C_1*El + C_0$

for each receiver available for the current Call for Proposals, a summary of these optimal values are reported in the following.

* **C-low receiver**: the parameters refer to a peak gain of 0.60 K/Jy at 52.2 degrees of elevation (*LHCP channel*) and to a peak gain of 0.64 K/Jy at 51.7 degrees of elevation (*RHCP channel*).  

========== ===================== ====================== 
Parameter  Value [deg] for LHCP  Value [deg] for RHCP  
========== ===================== ====================== 
$C_0$      0.57 ± 0.09           0.58 ± 0.1                          
$C_1$      0.0013 ± 0.0011       0.0025 ± 0.0027                            
$C_2$      -1.3e-5 ± 1.1e-5      -2.4e-5 ± 2.2e-5                            
========== ===================== ====================== 

* **C-high or M-band receiver**: OLD RESULTS

========== ======================= 
Parameter  Value [deg] for C-high  
========== =======================
$C_0$      0.545439                
$C_1$      0.00525597              
$C_2$      -4.55697e-5
========== =======================

C-high or M-band: valid from 2018.

* **K-band receiver**: OLD RESULTS

========== ======================
Parameter  Value [deg] for K-band
========== ======================
$C_0$      0.364897
$C_1$      0.00624137
$C_2$      -4.60020e-5
========== ======================

K-band: from Prandoni et al. (2017). The DPFU is 0.60 K/Jy.

Regarding new receivers in the Commissining Phase, old values of $C_0$, $C_1$ and $C_2$ are available for the L-band receiver. Results about others receivers will be presented in the next future.

* **L-band receiver**: OLD RESULTS

========== ======================== 
Parameter  Value [deg] for L-band** 
========== ======================== 
$C_0$         0.5061                
$C_1$         0.002390              
$C_2$         -0.000021             
========== ======================== 

L-band: from Orlati et al. 


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


