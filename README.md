# mexico-crime-maps

- This repository contains the final project for my Introduction to Data Science with R class. 

- Crime data was obtained from the crime incidence report updated monthly by the Secretariado Ejecutivo del Sistema Nacional de Seguridad Pública. 

- Population data was obtained from the 2010 census conducted by the Instituto Nacional de Estadística y Geografía.

# homicidios.Rmd

- CSV with official crime data is cleaned and organized.
- Parsed data is plotted into different maps.
- The main product of the script is an interactive map with total homicide count per state.

# homicidios_100k.Rmd

- CSV with official crime data is cleaned and organized.
- Homicide rate per 100,000 population is included by using total homicide count and population data (INEGI)
- Parsed data is plotted into different maps.
- The main product of the script is an interactive map displaying homicide rate per 100,000 population.

# crime_year_function.Rmd

- The tools used in the above scripts were replicated in this script to generate the following functions:

- crime_year(crime, year): User must enter two arguments: crime and year. The function will then generate an interactive map displaying total count of such crime in that specific year.

- crime_year_per100k(crime, year): User must enter two arguments: crime and year. The function will then generate an interactive map displaying rate per 100,000 of such crime in that specific year.
