.. toctree::

Introduction 
============

The Sardinia Radio Telescope is a 64-meter single-dish radio telescope. It is located in the Pranu Sanguni area of San Basilio, Sardinia, Italy, 
about 40 km north of Cagliari. 

Its state-of-the-art technology includes an active surface with 1008 panels, which allows observations at high frequencies (from 0.3 up to 115 GHz). 
There are three main focal points where reveivers can be placed: primary focus (currently hosting the L-P dual band receiver); gregorian focus (K-band receiver), and Beam Wave Guide focus (C-band receiver).
In total, the telescope can accomodate up to 20 receivers. A number of additional receivers are currently being planned and built. 

The telescope can be operated in single-dish or VLBI mode for radio astronomy, geodynamical studies or space science.

A general description of the SRT, including technical commissioning information and first light results, can be found in the technical commissioning paper:
`Bolli et. al, Journal of Astronomical Instrumentation, Vol. 4, Nos. 3 & 4 (2015) 1550008 <https://www.worldscientific.com/doi/abs/10.1142/S2251171715500087>`_.

Scientific tests and applications for the SRT are described in the following scientific validation paper:
`Prandoni et. al, A&A 608, A40 (2017) <https://www.aanda.org/articles/aa/abs/2017/12/aa30243-16/aa30243-16.html>`_.

Science done with SRT during its early-science run (2016) with the various hardware and software described below can be found here: `Science with SRT <http://www.srt.inaf.it/astronomers/science_srt/>`_. 

In the following sections, we outline information that is useful for observing with the SRT.

Antenna 
=======

The Sardinia Radio Telescope (SRT) is a 64-meter gregorian radio telescope with shaped optics, a quasi-parabolic main mirror and a quasi-elliptical subreflector. 

The antenna's main characheristics are:

.. list-table::
   :widths: 10 20

   * - Position
     - Pranu Sanguni, San Basilio, Sardinia
   * - Geodetic Coordinates 
     - Lat 39° 29' 34.93742" N;  Long 9° 14' 42.5764" E (WGS84)
   * - Optical configuration 
     - Primary, Gregorian & Beam Waveguide (BWG)
   * - Primary mirror diameter
     - 64 m
   * - Subreflector diameter
     - 8 m
   * - Focal positions
     - primary f/D = 0.33; Gregorian f/D = 2.34; Beam waveguide (BWG) f/D = 1.8
   * - Azimuth range
     - --90 to 450 degrees
   * - Elevation range
     - 5 -- 90 degrees
   * - Slew rate
     - 0.85 degrees/s in azimuth; 0.5 degrees/s in elevation
   * - Frequency coverage
     - 0.3 -- 115 GHz
   * - Primary surface accuracy
     - 300 μm rms
   * - Pointing accuracy (rms)
     - 2 -- 5"

Active surface

The primary reflector, which is 64 m across, is made of 1008 aluminium panels (with an RMS ≤ 65 μm each) driven by 1116 electromechanical actuators. This *active surface*
is designed to compensate for the gravitational deformations of the whole surface at different elevations.

The observer can choose among three configurations:

* shaped  in tracking (it adjusts according to the observed elevation position)
* parabolic  in fixed position (optimized for El=45°)
* parabolic  in tracking (it adjusts according to the observed elevation position)

The shaped configuration is used for receivers in the Gregorian and BWG foci, while the parabolic configurations are used for the Primary focus systems.

Receivers
=========

* The L-P band dual-frequency receiver was installed at the primary focus of the telescope, and therefore requires the parabolic configuration. It allows for simultaneous observations at L and P bands. The polarization type is linear but can be transformed to circular.

* A mono-feed C-high band receiver is installed at the Beam Wave Guide (BWG) focus of the telescope.

* A multi-feed K-band receiver is installed at the (secondary) Gregorian focus. Both C and K band receivers require the shaped configuration. 

In the following table, we outline, for each receiver: its frequency coverage, its beam-size in arcmin or arcsec, measurements of the system temperature at 45 degrees of elevation, and antenna gain. 
Each receiver feed allows for two polarizations.

======== ========================= =======   =================   ===============  ========= ========== ========== =========
Band     Frequency coverage (GHz)   Feeds    Polarization type   Focal position   Beam size Tsys (K)    Gain (%)  Sefd (Jy)
======== ========================= =======   =================   ===============  ========= ========== ========== =========
P         0.300 -- 0.360              1        linear              primary           56.2'   [50-80]       [45]     125
L         1.3 -- 1.8                  1        linear              primary           12.6'    25-35        [47]     36
C-high    5.7 -- 7.7                  1        circular           beam waveguide    2.8'      32-37(*)   48         43(*)
K         18 -- 26                    7        circular           gregorian         50"         90(**)   44         138(**)
======== ========================= =======   =================   ===============  ========= ========== ========== =========

[ ] is an estimate
(*) at 6.7 GHz
(**) at 22.3 GHz with opacity 0.1 and ground air temperature of 293K.

The FWHM beam size, as a function of the frequency f,  can be approximated by the following rule: FWHM(arcmin)=19.7/ f(GHz)

SRT receiver changes are quick, allowing for an efficient frequency agility. The selected receiver is set in its focal position within at most a few minutes.

Future receivers: the SRT was designed to accomodate up to 20 receivers. A 7-feed S-band receiver (3 -- 4.5 GHz) is undergoing testing and designed to be placed at the primary focus of the telescope (requiring the parabolic configuration). The receiver had its first light in November 2016 (for the central feed).  
Additionally, a number of high-energy receivers are being planned for the SRT. This includes a multi-feed W receiver and a cryocooled, 19-pixel dual-polarized Q-band system at the secondary/gregorian focus. 
 
More details about current and future receivers at Italian radio telescopes (SRT, Medicina and Noto) are included in this review document: `receivers <http://rx2017.inaf.it/RX2017/Review_v8.1.pdf>`_

RF filters
----------

Different RF filters are available for the LP-band receiver. Although it is a coaxial receiver package, the control system sees it as a group of three different receivers, each one with its own code:

For the PPP receiver (P-band), there is one available filter (L2):  300--360 MHz (needed to exclude RFI at higher frequencies).

These are available for the LLP (L-band) configuration:

	1.	all band, 1300--1800 MHz (no filter)
	2.	1320--1780 MHz
	3.	1350--1450 MHz (VLBI band)
	4.	1300--1800 MHz (band-pass)
	5.	1625--1715 MHz (VLBI band)

For the simultaneous LP configuration, all combinations of the above configurations are allowed.

Backends 
========

The frontend (receiver) outputs are connected to the backend instruments either by coaxial cables or optical fibers, depending on whether the backend is located in the main building or below the dish. The following backends, designed for specific scientific activities, are available at the site:

Total Power backend
-------------------

This is a single-band, seven-beam backend for continuum observations. Located just below the dish, this backend is formed by 14 voltage-to-frequency converters that digitize the incoming RF signals. Different IF inputs can be selected from three focal points. Different bandwidths (maximum bandwidth: 0.1 - 2.1 GHz) and attenuation levels can be selected.

This backend consists of 14 sections. Each section processes a single IF channel with a single polarization, as input. The signal is detected by a broadband square-law detector and then digitized by an A/D converter. The nominal IF band is 2 GHz (0.1-2.1 GHz). On-board filters can restrict the band to 250, 680, or 1200 MHz. The same boards also perform the focus selection for the SARDARA backend. Here are the possible configurations of the Total Power backend for different receivers:

======== ======== ====================== ==================
Receiver Sections Filters (MHz)          Sampling time (ms)
======== ======== ====================== ==================
K-band     14     300,680,1200,2000      1 -- 1000
C-band      2     300,680,1200,2000      1 -- 1000
L-band      2     2000                   1 -- 1000
P-band      2     680                    1 -- 1000
L-P dual    4     2000                   1 -- 1000 
======== ======== ====================== ==================

XARCOS
------

This is a seven-beam, narrow-band, digital spectro-polarimeter with 8x2 input channels. The working bandwidth is 135-240 MHz and the maximum number of spectral channels is 2x2048 per polarization and per output channel. The instantaneous bandwidth ranges between 0.488 and 62.5 MHz and the maximum effective spectral resolution is ~500 Hz.

XARCOS is a spectro-polarimeter with a maximum bandwidth of 62.5 MHz capable of processing up to 16 IFs, thus fitting the seven-feed dual polarization K-band receiver array SRT is equipped with. Because its dump time is set to 10 seconds, it is not suitable for OTF observations. 
The observer can select the following configurations:

* XK77, to use the full K-band array; each digital sample has a 6-bit range. Full-Stokes sections are recorded, each having a 62.5MHz bandwidth and 2048(x4) channels.
* XK03, to use the K-band feeds #0 and #3. Each feed outputs two full Stokes sections respectively having bandwidths of 62.5 MHz and 4 MHz and 2048(x4) channels. Each digital sample has an 8-bit range.
* XK06, to use the K-band feeds #0 and #6. Each feed outputs two full Stokes sections respectively having bandwidths of 62.5 MHz and 4 MHz and 2048(x4) channels. Each digital sample has an 8-bit range.
* XK00, to use only the K-band central feed. It outputs four full-Stokes sections respectively with bandwidths of 62.5 MHz, 8 MHz, 2 MHz and 0.5 MHz, each having 2048(x4) channels. Each digital sample has an 8-bit range.
* XC00 , to use the C-band receiver. It outputs four full-Stokes sections respectively with bandwidths of 62.5 MHz, 8 MHz, 2 MHz and 0.5 MHz.

Digital Base Band Converter (DBBC)
----------------------------------

This digital platform is based on a flexible architecture composed of four ADC boards, with 1 GHz of bandwidth each and four Xilinx FPGA boards for data processing. The platform is designed mainly for VLBI experiments; however, a wideband spectrometer has been developed for other purposes.

Pulsar Digital Filter Bank mark 3 (PDFB3)
-----------------------------------------

This is an FX correlator developed by the Australia Telescope National Facility (ATNF) that performs full-Stokes observations. It allows for four inputs, each with a 1024 MHz maximum bandwidth and 8-bit sampling for a high dynamic range. The DFB3 is suitable for precise pulsar timing and searching. It allows for up to 8192 spectral channels in order to counter the effects of interstellar dispersion.

The main available configurations for pulsar observations are the following:

========= ============= =============== ==================
Obs type  N. time bins  Bandwidth (MHz) N. frequency bins
========= ============= =============== ==================
folding   1024          1024            2048
folding   1024          1024            1024
folding   1024          1024            512
folding   1024          512             2048
folding   1024          512             1024
folding   1024          512             512
folding   512           1024            1024
folding   512           512             1024
folding   512           512             512
folding   512           256             512
folding   256           256             2048
folding   256           256             1024
search                  512             1024
search                  512             128
========= ============= =============== ==================

Further details about the DFB can be found in the ATNF `DFB manual <http://www.srt.inaf.it/media/uploads/astronomers/dfb.pdf>`_.

At the SRT, DFB observations are piloted using the SEADAS software. 

Additional, so-called *Maccaferri* filters are available at L-band at the level of the backends. The recommended filter for pulsar observations at L-band 
is the *WIDE* filter (460 MHz of bandwidth).


ROACH backend
-------------

This backend is an FPGA board developed by the CASPER collaboration, with two ADC converters and a reprogrammable architecture. It can be used to acquire baseband data (voltages) or for real-time folding of pulsar data, thanks to the PSRDADA software. The currently available bandwidth is 128 MHz using a CPU cluster with 8 nodes (each node processes 16 MHz, so 8 x 16 MHz in total).

The ROACH backend has been the backend of choice for the Large European Array for Pulsars (LEAP) project. More information on the implementation of the LEAP project with the ROACH backend can be found here: `Internal Report N. 39 <http://www.oa-cagliari.inaf.it/area.php?page_id=10&skip=3>`_. It is also used to perform all P-band pulsar observations at SRT. Its ability to perform coherent de-dispersion makes it a superior backend compared to the DFB. 

SARDARA
-------

SARDARA is a backend composed of seven fully-reconfigurable ROACH-2 boards that allow it to perform wide-band, full-Stokes observations. The many observing modes covered by SARDARA include: continuum, spectroscopy, spectro-polarimetry, as well as high-time resolution for pulsars and fast transients . Its sampling time can be set from 5ms to 1 s. It is the backend of choice for OTF spectro-polarimetric observations.
Available configurations consist of:

* 420 MHz bandwith with 1024 or 16384  channels
* 1500 MHz bandwidth with 1024 or 16384 channels

The 420 MHz configurations should only be used with the L-Band receiver and the following RF filters: (3) 1350 - 1450 MHz or (5) 1625 - 1715 MHz, in order to avoid aliasing.

SARDARA's spectral resolution and sensitivity is defined by its full 1500 MHz bandwidth. However only 1200 MHz of the full 1500 MHz bandwidth is usable, since the 1200 MHz filter of the Total Power backend is being used as input to SARDARA. 

More detailed information on the SARDARA backend can be found here: `SARDARA <https://www.worldscientific.com/doi/full/10.1142/S2251171718500046>`_. 

Calibration
===========

Pointing calibration
--------------------

Pointing model: this procedure was used to calculate the pointing errors compared to ideal conditions, at night without sunlight. Actual conditions could 
require pointing measurements to take into account possible errors due to environmental factors (pointing measurements can be included in the observation schedule).

* L-band

Values adopted same as Bolli et al (2015)

* C-band

========== ====================== ======================
Parameter  Value (deg) for C-band Value (deg) for K-band
========== ====================== ======================
Az-mean    +0.000440               +0.000850
Az-rms     +0.000790               +0.000870
El-mean    -0.001660               -0.001280
El-rms     +0.000910               +0.001200
========== ====================== ======================

Focus curve calibration
-----------------------

The focus curve is applied in real time. 

* C-band

We fit the curve with a polynomial of degree 6, such as: y = a x^6+ b x^5 + c x^4 + d x^3 + e x^2 + f x + g

========== ===================
Parameter  Value
========== ===================
a          2.36410838911e-08
b          -6.62393455442e-06
c          0.000733782714288
d          -0.040640240455
e          1.16941963489
f          -16.4202062811 
g          91.5590595452
========== ===================

* K-band

Gain curve calibration
----------------------

* L-band

Values adopted same as Bolli et al (2015)

* C-band

=========== ============== ==============
Parameter   Value (C-band) Value (K-band)
=========== ============== ==============
C0          0.545439        0.505427
C1          0.00525597      0.00864506
C2          -4.55697e-5     -6.37184e-5
=========== ============== ==============

C-band Time range valid from 2018.

K-band: from Prandoni et al. (2017).

Beam shape
----------

* C-band

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

* K-band

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
3C123(*)
3C295
========== =================== =========================

(*) 3C123 is partially resolved with the K-Band because its angular size is about 45 arcsec, therefore this source is not good enough as a calibrator for that frequency.

Pointing calibration: see Tarchi et al (2013) and Ricci et al (2016)


Useful links
============

A general description of the SRT, including technical commissioning information and first light results, can be found in the technical commissioning paper:
`Bolli et. al, Journal of Astronomical Instrumentation, Vol. 4, Nos. 3 & 4 (2015) 1550008 <https://www.worldscientific.com/doi/abs/10.1142/S2251171715500087>`_.

Scientific tests and applications for the SRT are described in the following scientific validation paper:
`Prandoni et. al, A&A 608, A40 (2017) <https://www.aanda.org/articles/aa/abs/2017/12/aa30243-16/aa30243-16.html>`_.

Science done with SRT during its early-science run (2016) with the various hardware and software described below can be found here: `Science with SRT <http://www.srt.inaf.it/astronomers/science_srt/>`_. 

Spectral-polarimetric techniques with SRT: `Sardinia Radio Telescope wide-band spectral-polarimetric observations of the galaxy cluster 3C 129 <https://arxiv.org/abs/1607.03636>`_.

User guide and observing modes
==============================

Instructions for observing at the SRT with different modalities (receivers, backends, modes) are provided here: `instructions <http://srt-procedures.readthedocs.io/en/latest/>`_

A complete manual about the Italian radio antennas is found here: `DISCOS <http://discos.readthedocs.io/en/latest/index.html>`_.

Observing tools
===============

Source visibilites can be determined using the `CASTIA online tool <http://www.ira.inaf.it/Observing/castia/site/index.php>`_.

The online Exposure Time Calculator (ETC) can be found here: `ETC tool  <http://www.ira.inaf.it/expotime/all_ETC.html>`_.


