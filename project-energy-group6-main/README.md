# project-energy-group6

# Dataset
We were given data in five minute increments for all of 2020 for two air conditioning chillers which both cool the Engineering Science Building. Importantly, these chillers are never run at the same time. This means that it will be feasible to calculate the efficiency of these chillers independently. The dataset consisted of 2 CSV files with 16 columns each with these 16 columns being the same for each chiller. Figure 2.1 illustrates the flow of the data for each chiller and the relationships between all of the columns in the dataset. The table below outlines the critical system parameters that are described in the following analyses .

| System Parameter | Description |
| -----------------|-------------|
|PowChi|The power that is being consumed by the chiller|
|TempAmbient|Average air temperature surrounding the chiller|
|RunChi|Value indicating the ON/OFF status off the chiller|
|Humidity|Amount of water vapor in the air measured as percent compared to max water vapor possible|
|Precip|Amount of rainfall measured in inches representing depth|
|Dew Point|Temperature at which the air must be cooled to become saturated with water vapor measured in Fahrenheit|
|Pressure|Indication of air pressure at the time measure in inches|
