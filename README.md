This project uses R to visualize and predict changes in the labor market using Bureau of Labor Statistics data.

This analysis is a continuation of the analysis done in [hiring_optimization_1](https://github.com/RileyHasling/hiring_optimization_1). Seeing hiring_optimization_1 first can provide helpful context for the below description. This analysis takes the OPV scores found in hiring_optimization_1 and uses R to visualize them from 2020 to 2024 and predict them for 2025.

According to the analysts, the 2024 job market will be worst for production/transportation, sales, and engineering employees (OPV = -1.436, -0.840, and -0.049, respectively).

This analysis uses R to clean, analyze, and visualize employment data from the Bureau of Labor Statistics's Current Population Survey. Raw Excel data was imported into R and the same cleaning was done to it as was done to the data in hiring_optimization_1. OPV scores were created the same way, as well. The visualization for this data is a bar graph with the x-axis being occupation and the y-axis being OPV score. The predictions of 2025 OPV scores were created using the unstandardized OPV scores for each occupation for each year and a linear regression model.
