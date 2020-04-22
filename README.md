# Data Assimilation of the COVID-19 pandemia using an augmented SIR model

Periodical update of [assimilated
Corona-Data](https://www.zenodo.org/record/3738945) based on the
[Johns-Hopkins
database](https://github.com/CSSEGISandData/COVID-19.git) and data
from the [Robert-Koch
Institut](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/Fallzahlen.html).
An updated overview of the assimilation is found on this page. The numerical
values, as well as the individual plots can be found in the
subfolders.

Maintained by Joern Sesterhenn and Gabriele Camerlengo.

## Legend
Confirmed Cases and Deaths from the JHU or RKI. Lines are assimilated results.  
The growth rate calculated from 
![\frac{\partial f_2}{\partial I}](https://render.githubusercontent.com/render/math?math=%5Cfrac%7B%5Cpartial%20f_2%7D%7B%5Cpartial%20I%7D)

## New York
![Linear Representation of the data](figs/US-New_York-New_York/da.png)
![Logarithmical Representation of the data](figs/US-New_York-New_York/da_log.png)
![Model parameter \beta](figs/US-New_York-New_York/da_beta.png)
![Model parameter \gamma and \deta](figs/US-New_York-New_York/da_delta_gamma.png)
![Contact number](figs/US-New_York-New_York/da_contact_number.png)
![Growth rate of infections](figs/US-New_York-New_York/da_A22.png)
![FFT of the growth rate](figs/US-New_York-New_York/da_FFT_A22.png)


