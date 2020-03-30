# Project 6 - Effect of State-Level Social Distancing Measures Implemented by the United States of America on Air Pollution Levels

This study examined the association between COVID-19 induced social distancing measures implemented at the state-level in the USA with levels of air pollution accounted for as PM 2.5 concentration. Air pollution data (PM 2.5) and social distancing dates were obtained for NY, CA, MA, IL, WA, and WI from January 2018 to March 2020. Additionally, population compliance with government mandated lockdowns was explored using satellite imagery from before and after COVID-19 induced lockdowns for three major US cities.

## Getting Started

Here is a list of the items contained in this repository:

- **[COVID19 Cases](https://github.com/COVID19-DVRN/Project-6---Effects-of-social-distancing-and-isolation-on-pollution/tree/master/COVID19%20Cases)**: folder containing extraction code for the number of incident cases per state from January 21st 2020 until March 28th 2020, from a [publicly available dataset](https://github.com/nytimes/covid-19-data). Folder also contains the data outputed from running the code. Updated data can be downloaded directly from the source and processed using the code with minor modifications. 

- **[Merging](https://github.com/COVID19-DVRN/Project-6---Effects-of-social-distancing-and-isolation-on-pollution/tree/master/Merging)**: folder containing code for merging COVID19 case data with PM 2.5 emission data and social distancing data. Folder also contains the data outputed from running the code.

- **[PM Emissions](https://github.com/COVID19-DVRN/Project-6---Effects-of-social-distancing-and-isolation-on-pollution/tree/master/PM%20Emissions)**: folder containing raw data files on PM 2.5 concentration (in μg/m3), retrieved from all atmospheric sensor stations in six states in the USA. Data was made freely available by the [United States Environmental Protection Agency](https://www.epa.gov/outdoor-air-quality-data/download-daily-data). Nested [Merged Pollution Data](https://github.com/COVID19-DVRN/Project-6---Effects-of-social-distancing-and-isolation-on-pollution/tree/master/PM%20Emissions/Merged%20Pollution%20Data) folder contains code for aggregating raw data and outputting a single value per day per state from January 2018 to March 2020. Folder also contains the data outputed from running the code.

- **[Social Distancing Levels](https://github.com/COVID19-DVRN/Project-6---Effects-of-social-distancing-and-isolation-on-pollution/tree/master/Social%20Distancing%20Levels)**: folder containing raw data files for level of social distancing measures implemented in 6 different states in the USA. Measurse were classified using 4 levels of lockdown from lowest to highest: normal level (no restrictions on movement), emergency state, school shut down and shelter-in-place. Data was categorized manually using [readily available websites](https://en.wikipedia.org/wiki/Timeline_of_the_2020_coronavirus_pandemic_in_the_United_States) categorized from January 2018 to March 2020.

- **[Statistical Analysis and Reporting (RMarkdown file)](https://github.com/COVID19-DVRN/Project-6---Effects-of-social-distancing-and-isolation-on-pollution/blob/master/Statistical%20Analysis%20and%20Reporting.rmd)**: Markdown file used for the analysis and reporting of the project.

- **[Statistical Analysis and Reporting (HTML file)](https://github.com/COVID19-DVRN/Project-6---Effects-of-social-distancing-and-isolation-on-pollution/blob/master/Statistical%20Analysis%20and%20Reporting.html)**: HTML file used for the analysis and reporting of the project.

