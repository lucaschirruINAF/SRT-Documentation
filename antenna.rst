.. toctree::

Introduction 
============

The Sardinia Radio Telescope is a 64-meter single-dish radio telescope. It is located in the Pranu Sanguni area of San Basilio, Sardinia, Italy, 
about 40 km north of Cagliari. 

Its state-of-the-art technology includes an active surface with 1008 panels, which allows observations at high frequencies (from 0.3 up to 115 GHz). 
There are three main focal points where reveivers can be placed: primary focus (currently hosting the L-P dual band receiver); Gregorian focus (K-band receiver), and Beam Wave Guide focus (C-band receiver).
In total, the telescope can accomodate up to 20 receivers. A number of additional receivers are currently being planned and built. 

The telescope can be operated in single-dish or VLBI mode for radio astronomy, geodynamical studies or space science. Its geographical location allows it
to observe at declinations above -33 degrees.

A general description of the SRT, including technical commissioning information and first light results, can be found in the technical commissioning paper:
`Bolli et. al, Journal of Astronomical Instrumentation, Vol. 4, Nos. 3 & 4 (2015) 1550008 <https://www.worldscientific.com/doi/abs/10.1142/S2251171715500087>`_.

Scientific tests and applications for the SRT are described in the following scientific validation paper:
`Prandoni et. al, A&A 608, A40 (2017) <https://www.aanda.org/articles/aa/abs/2017/12/aa30243-16/aa30243-16.html>`_.

Science done with SRT during its early-science run (2016) with the various hardware and software described below can be found here: `Science with SRT <http://www.srt.inaf.it/astronomers/science_srt/>`_. 

In the following sections, we outline information that is useful for observing with the SRT in the current call for proposals (published September 14, 2018 with a deadline of October 9, 2018). We note that remote observing is not currently available for the Sardinia Radio Telescope; each proposing team will need to send at least one observer to the SRT to prepare the observing schedules and perform the observations on site. 


Antenna 
=======

The Sardinia Radio Telescope (SRT) is a 64-meter Gregorian radio telescope with shaped optics, a quasi-parabolic main mirror and a quasi-elliptical subreflector. 

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

We note that while the elevation limits range from 5 to 90 degrees, observations should be planned for an elevation between 6 and 82 degrees. Only in
exceptional cases should the observations go below 6 degrees or above 82 degrees. 

Active surface

The primary reflector, which is 64 m across, is made of 1008 aluminium panels (with an RMS ≤ 65 μm each) driven by 1116 electromechanical actuators. This *active surface*
is designed to compensate for the gravitational deformations of the whole surface at different elevations.

The observer can choose among three configurations:

* shaped  in tracking (it adjusts according to the observed elevation position)
* parabolic  in fixed position (optimized for El=45°)
* parabolic  in tracking (it adjusts according to the observed elevation position)

The shaped configuration is used for receivers in the Gregorian and BWG foci, while the parabolic configurations are used for the primary focus systems.

Receivers
=========

In the current call for proposals, the following (cryogenically-cooled) receivers are available in both single-dish and VLBI modes:

=============== ============= =============== ================= =============== ================================================
RF band (GHz)       Type      Tsys@90degEL(K) Beamsize (arcmin) Max gain (K/Jy) connected backends
=============== ============= =============== ================= =============== ================================================
P 0.30-0.36     single-feed      50-80             48                 0.52        DBBC,ROACH1
L 1.3-1.8       single-feed      25-35             11.4               0.55       DFB,DBBC,ROACH1,SARDARA
C-high 5.7-7.7  single-feed      32-37             2.7                0.66       TP,DFB,DBBC,ROACH1,SARDARA,XARCOS
K 18-26.5        7-feed          90                0.8                0.66      TP (MB),DFB,DBBC,ROACH1,SARDARA (MB),XARCOS(MB) 
=============== ============= =============== ================= =============== ================================================

(MB) means that the Multi-Beam option is available for observations in K-band with the TP, XARCOS and SARDARA backends. 

* The single-feed, L-P band dual-frequency receiver was installed at the primary focus of the telescope, and therefore requires the parabolic configuration. It allows for simultaneous observations at L and P bands. The polarization type is linear but is also transformed to circular thanks to a hybrid converter. 

* A single-feed C-high band receiver is installed at the Beam Wave Guide (BWG) focus of the telescope. The polarization type is circular.

* A multi-feed K-band receiver is installed at the (secondary) Gregorian focus. Both C and K band receivers require the shaped configuration. The polarization type is circular.
 
In the following table, we outline, for each receiver: its frequency coverage; number of feeds; polarization type; focal position; its beam-size in arcmin or arcsec; measurements of the system temperature Tsys at 45 degrees of elevation and antenna gain. Each receiver feed allows for two polarizations.

======== ========================= =======   ========================== ================ ========== ========== =========== 
Band     Frequency coverage (GHz)   Feeds     native polarization type   Focal position  Beam size  Tsys (K)   Gain (K/Jy)  
======== ========================= =======   ========================== ================ ========== ========== =========== 
P         0.30 -- 0.36                1        linear                     primary          48'(*)     [50-80]      0.52     
L         1.3 -- 1.8                  1        linear                     primary         11.4'(*)     25-35       0.55     
C-high    5.7 -- 7.7                  1        circular                   beam waveguide   2.7'      32-37(*)   0.66 (*)         
K         18 -- 26                    7        circular                   Gregorian       0.8'(**)    90(**)     [0.66]    
======== ========================= =======   ========================== ================ ========== ========== ===========

[ ] is an estimate
(*) at the band's central frequency (for C-band: 45 degrees EL @ 7.3 GHz)
(**) at 22.3 GHz with opacity 0.1 and ground air temperature of 293K.

The FWHM beam size, as a function of the frequency f,  can be approximated by the following rule: FWHM(arcmin)=19.7/ f(GHz)

SRT receiver changes are quick, allowing for an efficient frequency agility. The selected receiver is set in its focal position within at most a few minutes.
However, the use of a Gregorian cover to limit RFI in L/P band observations does not currently allow a quick receiver change between L/P bands and other bands (C or K). Receiver changes between C and K-bands are not affected. 
An automatic system for the installation and removal of the Gregorian cover is currently under development and will permit smooth and efficient frequency changes.

Note about the L/P dual-band receiver: the RFI levels need to be minimized. The availability of the Gregorian cover for this purpose is not a priori guaranteed. 

Future receivers: the SRT was designed to accomodate up to 20 receivers. A 7-feed S-band receiver (3 -- 4.5 GHz) is undergoing testing and designed to be placed at the primary focus of the telescope (requiring the parabolic configuration). The receiver had its first light in November 2016 (for its central feed). The full commissioning of this receiver is expected to end in 2019.   
Additionally, a number of high-energy receivers are being planned for the SRT. This includes a multi-feed W receiver and a cryocooled, 19-pixel dual-polarized Q-band system at the secondary/Gregorian focus. 
 
More details about current and future receivers at Italian radio telescopes (SRT, Medicina and Noto) are included in this review document: `receivers <http://rx2017.inaf.it/RX2017/Review_v8.1.pdf>`_


LP-band Filters
----------------

Different RF filters are available for the LP-band receiver. Although it is a coaxial receiver package, the control system sees it as a group of three different receivers, each one with its own code:

For the PPP receiver (P-band), there is one available filter (with code L2XX for linear or C2XX for circular):  300--360 MHz (which is needed to exclude RFI at higher frequencies).

For the LLP (L-band) configuration, the following filters are available for linear or circular polarizations:

* XXL1 (for linear) or XXC1 (for circular):	all band, 1300--1800 MHz (no filter) (not recommended)
* XXL2 (for linear) or XXC2 (for circular):	1320--1780 MHz
* XXL3 (for linear) or XXC3 (for circular):	1350--1450 MHz (VLBI band)
* XXL4 (for linear) or XXC4 (for circular): 	1300--1800 MHz (band-pass)
* XXL5 (for linear) or XXC5 (for circular):	1625--1715 MHz (VLBI band)

For simultaneous LP observations, all combinations of the above configurations are allowed.


Backends 
========

The frontend (receiver) outputs are connected to the backend instruments either by coaxial cables or optical fibers, depending on whether the backend is located in the main building or below the dish. The following backends, designed for specific scientific activities, are available at the site:

These backends are available for the current call for proposals:

=============== ======= ===================== =============== ===================== ====================================================================== 
Backend          Bands   Bandwidth (MHz)      Sampling time   Max freq. bins        Observing modes                                  
=============== ======= ===================== =============== ===================== ====================================================================== 
**Total Power**   C,K   250,680,1200,2000     1-1000 ms          1                  continuum (analog)
**XARCOS**        C,K   0.5,2.0,7.8,62.5      10s               2048                spectro-polarimeter
**SARDARA**       C,K   420(300*),1500(1200*)  down to 5ms       1024 or 16384       spectro-polarimeter(*)    
**SARDARA**        L    420(100*),1500(500*)   down to 5ms       1024 or 16384       spectro-polarimeter(*)    
**DFB3**         L,C,K  256,512,1024          100 microsec      8192, pulsars: 2048  online pulsar folding + pulsar/transient search 
**ROACH1**      P,L,C,K         128             -             (varies)               baseband recorder + offline pulsar folding + pulsar/transient search
**DBBC**        P,L,C,K         512             -                -                   VLBI 
=============== ======= ===================== =============== ===================== ====================================================================== 
 
(*) For the 1500 MHz SARDARA configuration, the actual available RF bandwidth is 1200 MHz with the C-band and K-band receivers. 
Similarly, for the 420 MHz SARDARA configuration, the effective RF bandwidth is 300 MHz with the K-band and C-band receivers. Instead, the L-band receiver only has 500 MHz of RF bandwidth; when the SARDARA 420 MHz configuration is needed, the actual available RF bandwidth for SARDARA is 100 or 90 MHz, according to the selected receiver RF filter.

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

The full bandwidth for this receiver is 500 MHz (1.3-1.8 GHz). RF filters must be used (choose between XXL4, XXL2 etc.). For the 420 MHz configuration, the available filters are: XXL3, XXL5, XXC3 and XXC5 (to be selected following the needed sky frequency and polarization). We note that with these filters, the effective RF bandwidth is 100 MHz or 90 MHz. 

**SARDARA is offered in shared-risk mode in all of its configurations.**

More detailed information on the SARDARA backend can be found here: `SARDARA <https://www.worldscientific.com/doi/full/10.1142/S2251171718500046>`_. 

Calibration
===========

Pointing model
---------------

This calibration procedure was used to calculate the pointing errors in ideal conditions, i.e. at night without sunlight. Actual conditions will most likely 
require new pointing measurements in order to take into account possible errors due to environmental factors. Pointing measurements before starting an observing session are highly recommended
and can be included in the observation schedule.

In the table below, we report the calculated rms values in ideal conditions:

========== ====================== ======================= ======================
Parameter  Value (deg) for L-band  Value (deg) for C-band Value (deg) for K-band
========== ====================== ======================= ======================
Az-mean                                +0.000440               +0.000850
Az-rms       +0.001944(*)              +0.000790               +0.000870
El-mean                                -0.001660               -0.001280
El-rms       +0.001944(*)              +0.000910               +0.001200
========== ====================== ======================= ======================

(*) values for L-band from Bolli et al (2015)

Focus curve calibration
-----------------------

The focus curve is applied in real time. However, it is highly recommended that for C and K-band observations, the observer perform a focus calibration before starting an observing session. 

Gain curve calibration
----------------------

From the measured gain curves (Gain vs. Elevation), one fits a 2-degree polynomial with the parameters C0, C1 and C2:

gain (K/Jy) = C2 El^2 + C1 El + C0

=========== ============== ================ ===============
Parameter   Value (L-band) Value (C-band)    Value (K-band)
=========== ============== ================ ===============
C0           0.5061          0.545439        0.505427
C1           0.002390        0.00525597      0.00864506
C2           -0.000021       -4.55697e-5     -6.37184e-5
=========== ============== ================ ===============

L-band: from Orlati et al. 

C-band: valid from 2018.

K-band: from Prandoni et al. (2017).

Beam shape
----------

In the following tables, the second lobe and third lobe percentages correspond to the contribution of the counts in that lobe as compared to the
central beam. 

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


