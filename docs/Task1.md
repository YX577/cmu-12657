 [Task 2](Task2.md) | [Task 3](Task3.md) | [Resources](Resources.md) | [Main Page](https://mushimu.github.io/12657-project/)

## Task 1. Familiarize with Climate Model Output

## Overview

Analyses of long-term records show evidence that climate patterns have changed in many regions of the U.S. For instance, altering the fraction of precipitation that falls as rain, and enhancing snowpack melting (Rasmussen et al., 2011). These changes might extend into the future, because the emission of greenhouse gases (GHG) will continue affecting the atmospheric composition and overall conditions of the Earth’s climate.

There is particular concern about the potential future conditions in places where vulnerability is high. For instance, snowpack provide a vital water resource for the western U.S. (Liu et al., 2017). Therefore, we need to understand the potential climate change impacts in the Yakima River Basin.


![Fig. 1 Yakima River Basin in the state of Washington](https://mushimu.github.io/12657-project/images/YakimaRiverBasinCities.png)
_Fig. 1 - Yakima River Basin in the state of Washington)_

General Circulation Models or Global Climate Models (GCM) provides us a way to simulate the climate of the Earth under different conditions (such as higher concentrations of GHG in the atmosphere) to understand what are the potential consequences. We will use a set of simulations from the National Atmospheric Research Center (NCAR) to study the consequences of climate change in the Yakima River Basin.

----
## Learning Objectives

1. Familiarize with the concept of General Circulation Models or Global Climate Models, as well as Regional Climate Models
2. Understand the limitations of current climate modeling
3. Differentiate between the different methods to analyze climate change impacts at higher resolutions
4. Understand the tradeoffs between methods
5. Learn about the different datasets available to study climate change impacts
6. Familiarize specifically with the Pseudo Global Warming (PGW) Dynamical Downscaling approach using the WRF High Resolution Simulations of Current and Future Climate of North America from NCAR

----
## Climate Models to study impacts of Climate Change

To study climate change, usually, a General Circulation Model (GCM) that models the physical processes that occur at different levels of the atmosphere and its interaction with the land and the ocean, will be used.

In these types of models, the Earth is divided into thousands of grid cells and vertical levels and many different processes need to be taken into account so that they are relatively consistent with reality. Computational time can be a heavy burden, so the ease the simulation, the resolution of the mesh covering the Earth is very coarse. At this point, GCM simulations can only imitate average conditions and many of them show substantial biases in different aspects of the water cycle (Prein et al., 2017). Additionally, in regions where the terrain is complex, such as the Western U.S., the coarse resolution of GCM does not allow for simulating well climate conditions(Rasmussen et al., 2011).

To overcome these issues, Regional Climate Models (RCM) designed via downscaling techniques, are used. These models typically use higher resolutions (about ~25km by 25km).

There are two main downscaling techniques.

1. **Statistical Downscaling** (SD) attempts to find a statistical relationship between large scale drivers and local drivers, so that the same relationship can be applied to the low-resolution GCM outputs and find an output at a higher resolution. Some issues with this approach are related to data scarcity.

2. **Dynamical Downscaling** (DD) uses the GCM output as boundary conditions to another model for which the study area is much smaller. However, depending on how the DD technique is specified, it might also take  long computational time. One DD setting is the **Pseudo Global Warming** (PGW) scheme.

    - The PGW scheme consist in perturbing the observed conditions with a change signal from an ensemble of GCM runs of future scenarios (Liu et al., 2017). Successful applications of these scheme are noted in (Rasmussen et al., 2014, 2011) over the Colorado Headwaters.


----

## The Weather Research Forecast (WRF) model High-resolution Simulations of Current and Future Climate of North America


[Weather Research Forecast (WRF)](https://en.wikipedia.org/wiki/Weather_Research_and_Forecasting_Model) numerical climate prediction model, has been used coupled with a PGW approach covering the Continental United States has been completed (Liu et al., 2017), and the data is available for your team to analyze.

This data, available through the [NCAR Research Data Archive](https://rda.ucar.edu/datasets/ds612.0/) is a high-resolution climate change simulation that resolves mesoscale orography at 4km, among other features (Rasmussen & Liu, 2017).

The boundary conditions for the model were taken from the ERA-Interim reanalysis data (You can read more about that dataset [here]( https://www.ecmwf.int/en/forecasts/datasets/archive-datasets/reanalysis-datasets/era-interim).)

The dataset consists in two different runs covering the period between **October 2000 and September 2012**.

### WRF Simulations

1. Retrospective run using ERA-Interim as boundary conditions.
2. The second is a simulation of the future climate, in which the ERA-Interim conditions were modified by adding the CMIP5 ensemble mean of the RCP 8.5 scenario (You can read more about the CMIP5 ensemble of GCM from different research institutions [here]( https://cmip.llnl.gov/), and about the RCP8.5 scenario [here]( http://sedac.ipcc-data.org/ddc/ar5_scenario_process/RCPs.html).)


----

## Quiz

Take the [quiz](https://forms.gle/DiU36AJLSuiMTk7r7) to mark this task as complete. You can refer to the content in this task and the content of the [presentation slides from Monday](12657-GuestLecture.pdf) to answer the quiz.


----

## Recommended readings

- Easterling, K.E. Kunkel, J.R. Arnold, T. Knutson, L.R. Leung, R.S. Vose, D.E. Waliser, & M.F. Wehner. (2017). Precipitation change in the United States (No. Volume I; pp. 207–230). Retrieved from U.S. Global Change Research Program website: https://science2017.globalchange.gov/chapter/7/



----
## References

- Liu, C., Ikeda, K., Rasmussen, R., Barlage, M., Newman, A. J., Prein, A. F., … Yates, D. (2017). Continental-scale convection-permitting modeling of the current and future climate of North America. Climate Dynamics, 49(1), 71–95. https://doi.org/10.1007/s00382-016-3327-9

- Prein, A. F., Liu, C., Ikeda, K., Trier, S. B., Rasmussen, R. M., Holland, G. J., & Clark, M. P. (2017). Increased rainfall volume from future convective storms in the US. Nature Climate Change, 7(12), 880.

- Rasmussen, R., Ikeda, K., Liu, C., Gochis, D., Clark, M., Dai, A., … Zhang, G. (2014, June 4). Climate Change Impacts on the Water Balance of the Colorado Headwaters: High-Resolution Regional Climate Model Simulations [research-article]. https://doi.org/10.1175/JHM-D-13-0118.1

- Rasmussen, R., & Liu, C. (2017). High Resolution WRF Simulations of the Current and Future Climate of North America. Research Data Archive at the National Center for Atmospheric Research, Computational and Information Systems Laboratory. https://doi.org/10.5065/D6V40SXP

- Rasmussen, R., Liu, C., Ikeda, K., Gochis, D., Yates, D., Chen, F., … Gutmann, E. (2011, June 15). High-Resolution Coupled Climate Runoff Simulations of Seasonal Snowfall over Colorado: A Process Study of Current and Warmer Climate [research-article]. https://doi.org/10.1175/2010JCLI3985.1
