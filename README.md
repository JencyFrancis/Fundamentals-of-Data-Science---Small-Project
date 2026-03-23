Overview :
This small project analyses an airline's daily performance over three years — 2021, 2022, and 2023 — using the airline3.csv dataset. 

The Dataset:
The dataset is airline3.csv — a comma-separated file with three columns: date (in yyyy-mm-dd format), number of passengers carried that day (in thousands), and average ticket price on that date (in Euros). It covers daily records across 2021, 2022, and 2023, giving roughly three years of airline performance data to work with.

The Figures:
There are two figures in the report, and they work together to tell the story of periodicity in the airline's passenger data.
Figure 1 is a bar plot with month on the x-axis and total passengers in thousands on the y-axis. This is where the Fourier transform comes in.Figure 2 is the power spectrum plot, with period in weeks on the x-axis and power on the y-axis. 

Key Technical Notes:
All angles in the analysis are in radians unless stated otherwise. When rounding any computed values, at least two significant digits are kept throughout. The code is written as a plain .py script and is fully human-readable — no external dependencies beyond numpy, pandas, and matplotlib are required.

Conclusion:
To conclude, it can be said that we observe the highest peak in July and August months due to summer season and in April and December basis the Fourier Analysis and Fit. The power spectrum displays the prediction of passenger travel, following a trend on a recurring pattern every year with December being the highest followed by January being the second highest.
