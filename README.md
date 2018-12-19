# <a name="top"></a> SOAR_Goodman_QuickReduce
SOAR-4m Goodman Spectrograph "Quick Reduce" package.

Purpose: Perform basic quick-and-dirty processing and wavelength- and spectrophotometric calibration of spectra obtained on the SOAR-4m Goodman spectrograph for the purpose of real-time "by eye" spectral classification.  Basically, SOAR_Goodman_QuickReduce fills the niche between IRAF implot (or SAOimage projection plots) and publication-quality full spectroscopic reductions.

## FAQ

* [What are the software dependencies?](#dependencies)
* [What data are needed?](#data)
* [How to run SOAR_Goodman_QuickReduce?](#howtorun)
* [How to request updates to the code or to the FAQ?](#requests)

----------------------------------------------------------------------

#### <a name="dependencies"></a>What are the software dependencies?

DECam_PGCM is written in Python 2.7.  It makes substantial use of the following python modules:
<ul>
<li> numpy (written using numpy 1.9.1, but similar or later versions should also work fine)
<li> scipy (written using scipy 0.14.0, but similar or later versions should also work fine)
<li> pandas (written using pandas 0.15.2, but similar or later versions should also work fine)
</ul>

[Back to top.](#top)

----------------------------------------------------------------------

#### <a name="data"></a>What data are needed?


<ul>
<li> A FITS file containing the SOAR Goodman spectrum of the target.
<li> A FITS file containing the SOAR Goodman spectrum of an ["Hamuy Tertiary Spectrophotometric Standard Star"](http://www.ctio.noao.edu/soar/content/hamuy-spectrophotometric-standards) obtained with the same Goodman configuration as the target spectrum (and preferably obtained during the same night), for removing the instrumental response of the detector.
<li> One comparison arc spectrum, for manually identifying the wavelegnth and column number of a single comparison arc line (for quick and-dirty-wavelength calibration).
<li> No bias frames or flat fields are needed for this basic quick-and-dirty processing and calibration.
</ul>

[Back to top.](#top)

----------------------------------------------------------------------

#### <a name="howtorun"></a>How to run SOAR_Goodman_QuickReduce?

*Under construction...*

[Back to top.](#top)

----------------------------------------------------------------------

#### <a name="requests"></a>How to request updates to the code or to the FAQ?

Please use the [issues](https://github.com/DouglasLeeTucker/SOAR_Goodman_QuickReduce/issues) to post requests for additions or other updates
to the code or to this FAQ .

[Back to top.](#top)

----------------------------------------------------------------------
