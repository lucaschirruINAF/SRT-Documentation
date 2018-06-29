.. toctree::

Introduction 
============

The Sardinia Radio Telescope is a 64-meter single-dish radio telescope. It is located in the Pranu Sanguni area of San Basilio, Sardinia, Italy, 
about 40 km north of Cagliari. 

Its state-of-the-art technology includes an active surface with 1008 panels, which allows observations at high frequencies (up to 115 GHz). Receivers can be placed in the
focus of the parabolic dish (currently: L,P and S band receivers). SRT's K-band receiver is located at the Gregorian focus, while SRT's C-band receiver is located at the Beam Wave Guide (BWG) focus.
In total, the telescope can accomodate up to 20 receivers. A number of additional receivers are currently being planned and built.

The telescope can be operated in single-dish or VLBI mode for radio astronomy, geodynamical studies or space science.

A general description of the SRT, including technical commissioning information and first light results, can be found in the technical commissioning paper:
`Bolli et. al, Journal of Astronomical Instrumentation, Vol. 4, Nos. 3 & 4 (2015) 1550008 <https://www.worldscientific.com/doi/abs/10.1142/S2251171715500087>`_

Scientific tests and applications for the SRT are described in the following scientific validation paper:
`Prandoni et. al, A&A 608, A40 (2017) <https://www.aanda.org/articles/aa/abs/2017/12/aa30243-16/aa30243-16.html>`_

In the following sections, we outline information that is useful for observing with the SRT.

Antenna 
=======

The Sardinia Radio Telescope (SRT) is a 64-meter gregorian radio telescope with shaped optics, a quasi-parabolic main mirror and a quasi-elliptical subreflector. 

The antenna's main characheristics are:

.. list-table::
   :widths: 10 20

   * - Position
     - Pranu Sanguni, San Basilio, Sardinia
   * - Coordinates 
     - Lat 39° 29' 34.93742" N;  Long 9° 14' 42.5764" E
   * - Optical configuration 
     - Gregorian & Beam Waveguide (BWG)
   * - Primary mirror diameter
     - 64 m
   * - Subreflector diameter
     - 8 m
   * - Focal positions
     - primary f/D = 0.33; Gregorian f/D = 2.34; Beam waveguide (BWG) f/D = 1.8
   * - Azimuth range
     - --90 -- 450 degrees
   * - Elevation range
     - 5 -- 90 degrees
   * - Slew rate
     - 0.85 degrees/s in azimuth; 0.5 degrees/s in elevation
   * - Frequency coverage
     - 0.3 -- 115 GHz
   * - Primary surface accuracy
     - 65 μm rms
   * - Pointing accuracy (rms)
     - 2 -- 5"

Active surface

The primary reflector, which is 64 m across, is made of 1008 aluminium panels (with RMS ≤ 65 μm) driven by 1116 electromechanical actuators. This *active surface*
is designed to compensate for the gravitational deformations of the whole surface at different elevations.

The observer can choose among three configurations:

* shaped  in tracking (it adjusts according to the observed elevation position)
* parabolic  in fixed position (optimized for El=45°)
* parabolic  in tracking (it adjusts according to the observed elevation position)

The shaped configuration is used for receivers in the Gregorian and BWG foci, while the parabolic configurations are used for the Primary focus systems.

Receivers
=========

* The L-P band dual-frequency receiver was installed at the primary focus of the telescope, and therefore requires the parabolic configuration. It allows for simultaneous observations at L and P bands. The polarization type is linear but can be transformed to circular.

* A mono-feed C-band receiver is installed at the Beam Wave Guide (BWG) focus of the telescope.

* A multi-feed, secondary focus K-band receiver is installed at the Gregorian focus. Both C and K band receivers require the shaped configuration. 

* A multi-feed S-band receiver is undergoing testing and is placed at the primary focus of the telescope (requiring the parabolic configuration). 

In the following table, we outline, for each receiver: its frequency coverage, its beam-size in arcmin/arcsec, measurements and estimations of the system temperature at 45 degrees of elevation, and antenna gain. 
All receivers allow for two polarizations.

======== ========================= =======   =================   ===============  ========= ========== ========== =========
Band     Frequency coverage (GHz)   Feeds    Polarization type   Focal position   Beam size Tsys (K)    Gain (%)  Sefd (Jy)
======== ========================= =======   =================   ===============  ========= ========== ========== =========
P         0.305 -- 0.410              1        linear              primary           56.2'        65?       45?     125
L         1.3 -- 1.8                  1        linear              primary           12.6'        21?       47?     36
S         3.0 -- 4.5                  7        linear              primary             ?        ?        ?
C         5.7 -- 7.7                  1        circular           beam waveguide    2.8'      26/33?    48?         43
K         18 -- 26.5                  7        circular           gregorian         50"     70 -- 90    44?         138
======== ========================= =======   =================   ===============  ========= ========== ========== =========

The FWHM beam size, as a function of the frequency f,  can be approximated by the following rule: FWHM(arcmin)=19.7/ f(GHz)

SRT receiver changes are quick, allowing for an efficient frequency agility. The selected receiver is set in its focal position within at most a few minutes.

* Future receivers: the SRT was designed to accomodate up to 20 receivers. Besides the S-band receiver which has already been tested and had its first light (November 2016), a number of high-energy receivers are being planned for the SRT. This includes a multi-feed W receiver and a secondary-focus, cryocooled, 19-pixel dual-polarized Q-band system.
 
More details about current and future receivers at Italian radio telescopes (SRT, Medicina and Noto) are included in this review document: `receivers <http://rx2017.inaf.it/RX2017/Review_v8.1.pdf>`_


Pointing calibration
--------------------

to be inserted here

Gain curve calibration
----------------------

to be inserted here

RF filters
----------

Different RF filters are available for the LP-band receiver. Although it is a coaxial receiver package, the control system sees it as a group of three different receivers, each one with its own code:

For the PPP receiver (P-band), available filters are:

	#.	all band, 305--410 MHz (no filter)
	#.	310--350 MHz
	#.	305--410 MHz (band-pass filter, sharper band edges).

These are available for the LLP (L-band) configuration:

	#.	all band, 1300--1800 MHz (no filter)
	#.	1320--1780 MHz
	#.	1350--1450 MHz (VLBI band)
	#.	1300--1800 MHz (band-pass)
	#.	1625--1715 MHz (VLBI band)

For the simultaneous LP configuration, all combinations of the above configurations are allowed.

Additional, so-called *Macaferri* filters are available at the level of the backends. They are: (to be included here).

Backends 
========

The frontend (receiver) outputs are connected to the backend instruments either by coaxial cables or optical fibers, depending on whether the backend is located in the main building or below the dish. The following backends, designed for specific scientific activities, are available at the site:

Total Power backend
-------------------

This is a single-band, seven-beam backend for continuum observations. Located just below the dish, this backend is formed by 14 voltage-to-frequency converters that digitize the incoming RF signals. Different IF inputs can be selected from three focal points. Different bandwidths (maximum bandwidth: 0.1 - 2.1 GHz) and attenuation levels can be selected.

This backend consists of 14 sections. Each section processes a single IF channel with a single polarization, as input. The signal is detected by a broadband square-law detector and then digitized by an A/D converter. The nominal IF band is 2 GHz (0.1-2.1 GHz). On-board filters can restrict the band to 250, 680, or 1200 MHz. The same boards also perform the focus selection for the SARDARA backend.


Pulsar Digital Filter Bank mark 3 (PDFB3)
-----------------------------------------

This is a FX correlator developed by the Australia Telescope National Facility that allows full-Stokes observations. It allows for four inputs, each with a 1024 MHz maximum bandwidth, and 8-bit sampling for a high dynamic range. The DFB3 is suitable for precise pulsar timing and searching, spectral line and continuum observations with a high time resolution. It allows for up to 8192 spectral channels in order to counter the effects of interstellar dispersion when it is operated in pulsar mode, and for power spectrum measurements in spectrometer mode.

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

ROACH backend
-------------

This backend is an FPGA board developed by the CASPER collaboration, with two ADC converters and a reprogrammable architecture. It can be used to acquire baseband data (voltages) or for real-time folding of pulsar data. The currently available bandwidth is 128 MHz thanks a CPU cluster with 8 nodes (each node processes 16 MHz, so 8 x 16 MHz in total).

SARDARA
-------

This backend can be used as a spectro-polarimeter and is based on 7 ROACH2 boards.

SARDARA is a wide-band ROACH-2 based backend for full-Stokes continuum and spectral lines observations.The sampling time can be set from 5ms to 1 s. It is the backend of choice for OTF spectro-polarimetric observations.
Available configurations are:

* 300 MHz bandwith with 1024 or 16384  channels
* 1500 MHz bandwidth with 1024 or 16384 channels

Currently, the 300 MHz configurations should be used only with the L-Band receiver and the RF filters: 1350 - 1450 MHz or 1625 - 1715 MHz, in order to avoid aliasing.

User guide
==========

Instructions for observing at the SRT with different modalities (receivers, backends, modes) are provided here: `instructions <http://srt-procedures.readthedocs.io/en/latest/>`_

A complete manual about the Italian radio antennas is found here: `DISCOS <http://discos.readthedocs.io/en/latest/index.html>`_

Observing tools
===============

Source visibilites can be determined using the `CASTIA online tool <http://www.ira.inaf.it/Observing/castia/site/index.php>`_.

.. note:: This is really interesting stuff. Thanks for reading.


