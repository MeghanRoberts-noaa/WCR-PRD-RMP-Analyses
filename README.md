This repository is a scientific product and is not official communication of the National Oceanic and Atmospheric Administration, or the United States Department of Commerce. All NOAA GitHub project code is provided on an ‘as is’ basis and the user assumes responsibility for its use. Any claims against the Department of Commerce or Department of Commerce bureaus stemming from the use of this GitHub project will be governed by all applicable Federal law. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by the Department of Commerce. The Department of Commerce seal and logo, or the seal and logo of a DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by DOC or the United States Government.

About this repo:

This project contains scripts that have analyses for the 2024 PSC 1-yr Biop, the PSC RMP and the SRKW prey reduction memo. Some scripts have associated html files that essentially display the information in a more visually appealing format. Relevant figures are saved in the "saved_figures" folder. Here are the scripts and a brief description:

Impacts_Area7_Fisheries:
This file contains figures showing actual vs projected catch for MA 7, the spatial overlap between SRKW and SRKW births and deaths, number of days open to Chinook retention, number of anglers per day in July, and Fraser Chinook run size. 

Prey_Reduction_Tech_Memo_24:
Contains cumulative prey reduction by timestep for the tech memo Meg Wallen is producing about reduction in Chinook prey for SRKW.

PSCHMP_Actual_Projected:
Compares actual vs projected catch for MA 5-7 and commercial fisheries (including bycatch and bycatch mortality) in the Srait of Juan de Fuca and the San Juan Islands.

Soundwatch_incidents:
Contains figures showing the number of incidents per day on days when the fishery was open in MA 7 for both commercial and recreational fisheries. 

SRKW_buffer_map:
This exploratory analysis looked at where SRKW sightings were on a day open to recreational fishing. This showed that the 1,000 yard rule will essentially close the area between the Canadian marine border and the west coast of San Juan island when the whales are present since this is such a small region and the whales are normally dispersed.

SRKW_rec_map:
This exploratory analysis looked at where SRKW where spotted by Soundwatch while recreational fishing was open and closed. This was plotted against the aerial vessel surveys to see if the whales were seen in the same areas as the vessels. Lack of data made it difficult to make any conclusions.

Validation_run_data:
Analysis of the validation run data used in the 2024 1-yr Puget Sound biop. Looking at starting abundances, nominal reductions, percent reductions, etc. Information for tech memo is also pulled from here.

If any of the scripts do not load, make sure to install all packages that are loaded (library(here)). To install use install.packages("here").