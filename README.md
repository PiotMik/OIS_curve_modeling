# OIS_curve_modeling

Repository with materials for presentation on OIS curve modeling for AGH Exotic Options seminar.

---
<img align="left" width="400" src="https://github.com/PiotMik/OIS_curve_modeling/blob/main/OIS_term_structure.PNG">


### Overview
We build a custom statistical model of GBP OIS curve movements with the purpose of presenting a range of techniques used for interest rate modeling. For the SONIA benchmark rate we employ a Hull-White model to accomodate expert-based level forecasts. Principal Component Analysis is used for dimensionality reduction in the longer end of the curve, which  allows to simultaneously model multiple tenors by means of curve shift, tilt and convexity. For the intermediate tenors we use a LASSO regression approach and spline interpolation.

The whole model is wrapped by a Monte Carlo algorithm which allows to simulate the curve movement on a daily granularity. 
<br><br><br>

---
<img src="https://www.agh.edu.pl/fileadmin/default/templates/images/uczelnia/siw/znak/symetryczny/en/dwuwiersz/agh_nzw_s_en_2w_wbr_rgb_150ppi.jpg" alt="AGH University logo" width="100"/>  
