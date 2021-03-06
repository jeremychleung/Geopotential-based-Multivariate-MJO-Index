<!-- # Geopotential-based Multivariate MJO Index (GMM Index) -->
Geopotential-based Multivariate MJO Index (GMM Index)
=====
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6331380.svg)](https://doi.org/10.5281/zenodo.6331380)<br />
This repository contains the data of the Geopotential-based Multivariate MJO Index (GMM Index).
<br /> <br />
 
<!-- **Overview**
-----
- This repository contains the data of the Geopotential-based Multivariate MJO Index (GMM Index).
 <br />  -->

**About the GMM Index**
-----
- The GMM index is an RMM-like index, derived from outgoing longwave radiation (OLR), 200hPa and 850hPa zonal wind, that can be extended to the pre-satellite era where satellite-based OLR data is unavailable. 
- The short record of OLR observation limits the data length of the RMM index ([Wheeler and Hendon, 2004](https://journals.ametsoc.org/view/journals/mwre/132/8/1520-0493_2004_132_1917_aarmmi_2.0.co_2.xml)), hindering the research of long-term variability of the Madden-Julian Oscillation (MJO) in the past century. And, the GMM index, which can be extended to the early 20th century (and even to the 19th century), is proposed to solve the problem.
- The construction method of the GMM index is the same as the RMM index, except that:
  -  the OLR input is derived from upper-tropospheric geopotential data, based on the intrinsic relationship between MJO convection and upper-level geopotential (see [Leung and Qian, 2017](https://doi.org/10.1007/s00382-016-3431-x));
  -  the OLR, 200hPa and 850hPa zonal wind input of the GMM index are bandpass-filtered anomalies. 
- Please refer to [Leung et al. (2022)](https://doi.org/10.1007/s00382-022-06142-2) for more detail about the calculation procedure and the theory behind it.
 <br /> 
 
**Files**
-----
- GMM index derived based on the ERA-Interim reanalysis
  - Location: [data/gmm_index_erai.csv](https://github.com/jeremychleung/Geopotential-based-Multivariate-MJO-Index/blob/main/data/gmm_index_erai.csv)
  - Temporal coverage: 1979–2013
- GMM index derived based on the ERA-20C reanalysis
  - Location: [data/gmm_index_era20c.csv](https://github.com/jeremychleung/Geopotential-based-Multivariate-MJO-Index/blob/main/data/gmm_index_era20c.csv)
  - Temporal coverage: 1900–2010
- GMM index derived based on the NOAA-20CRv3 reanalysis
  - Link: (to be uploaded)
  - Temporal coverage: 1836–2015
<br /> 

**Citation**
-----
If you use the GMM index in a publication or for any other purposes, please cite 
- Leung, J.CH., Qian, W., Zhang, P. et al. Geopotential-based Multivariate MJO Index: extending RMM-like indices to pre-satellite era. Clim Dyn (2022). https://doi.org/10.1007/s00382-022-06142-2
- Zenodo archive: https://doi.org/10.5281/zenodo.6331379
<br /> 

**References**
-----
- Leung, J.CH., Qian, W., Zhang, P. et al. Geopotential-based Multivariate MJO Index: extending RMM-like indices to pre-satellite era. Clim Dyn (2022). https://doi.org/10.1007/s00382-022-06142-2
- Leung, J.CH., Qian, W. Monitoring the Madden–Julian oscillation with geopotential height. Clim Dyn 49, 1981–2006 (2017). https://doi.org/10.1007/s00382-016-3431-x
- Wheeler, M.C., Hendon, H.H. An All-Season Real-Time Multivariate MJO Index: Development of an Index for Monitoring and Prediction. Mon Weather Rev 132:1917–1932 (2004). https://journals.ametsoc.org/view/journals/mwre/132/8/1520-0493_2004_132_1917_aarmmi_2.0.co_2.xml
<br /> 

**Contact**
-----
If you have any questions about the data, feel free to contact Dr. Jeremy Leung (chleung@pku.edu.cn or liangzx@gd121.cn).
<br /> 
