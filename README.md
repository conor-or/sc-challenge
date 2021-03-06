# Substructure detection challenge

![](index.png)
_Examples rendered with HST resolution, PSF, and noise. Ticks are 2 arcsec_

* Two mass functions, A and B (one cold one warm), with the same 10 systems for both.
* `/mass_function_*/*_image.fits` Files contain the lensed source emission only, no PSF and no noise, units are Wm<sup>-2</sup>arcsec<sup>-2</sup>#
* `/mass_function_*/*_mock.fits` files contain the HST mock
* HST PSF is in `/psf.fits`
* Noise realisations are the same for each system across mass functions
* Z_lens, Z_source and the RMS of the noise are in `/lens_data.txt`
* Pixel scale is 0.01 arcsec in unobserved emission, 0.04 arcsec in HST mocks, field of view is 10 arcsec

Lens and source redshifts below

| Catalogue # | Z_Lens | Z_Source |
| --- | --- | --- |
| 98809       | 1.034 | 3.013 |
| 129086      | 0.630 | 3.561 |
| 198127      | 0.568 | 2.435 |
| 203646      | 0.564 | 2.225 |
| 233212      | 1.165 | 2.629 |
| 334130      | 0.665 | 2.534 |
| 343381      | 1.563 | 3.231 |
| 413636      | 0.883 | 2.962 |
| 427853      | 0.835 | 1.972 |
| 523205      | 1.181 | 3.337 |
