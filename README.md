# Company Name: AirGuard Analytics 
## Overview
This project aims to predict air quality, specifically focusing on PM2.5 levels, using time series analysis. PM2.5 refers to fine particulate matter with a diameter of less than 2.5 micrometers, which can penetrate deep into the human respiratory tract and significantly affect health. Predicting PM2.5 levels is crucial for public health and environmental policy planning.
## Business Problem

In rapidly industrializing regions air pollution has emerged as a critical environmental and public health issue. The challenge faced by local authorities, environmental agencies, and public health organizations is the lack of predictive capability regarding air quality. This project aims to address this real-world problem by developing a predictive model for air pollution in Gucheng. The model's forecasts can be used by these stakeholders to implement timely health advisories, pollution control measures, and urban planning strategies.

## Stakeholders

- Local Government and Environmental Agencies: These bodies are responsible for monitoring and managing air quality, implementing pollution control policies, and safeguarding public health.
- Public Health Organizations: They require accurate air quality data to issue health advisories and to study the long-term impact of air pollution on health.
- General Public: Especially vulnerable groups like children, the elderly, and individuals with respiratory conditions.
- Businesses and Industries: Particularly those whose operations contribute to air pollution and are affected by regulations.

## Business Objective

The predictive model will empower stakeholders with foresight into air quality trends, enabling proactive measures rather than reactive responses. For instance, health advisories can be issued in advance, and industries can adjust operations in anticipation of high pollution periods. This approach not only mitigates the health impacts of air pollution but also aids in efficient resource allocation for pollution control.

## Data Understanding

Our dataset is obtained from __[UC Irvine ML Repository](https://archive.ics.uci.edu/dataset/381/beijing+pm2+5+data)__ . This data has values recorded hourly from air quality monitoring sites.<br>

The data set covers the time span from March 1st, 2013, to February 28th, 2017. The following presents details for each feature/column : <br>

- `No`: row number
- `year`: year of data in this row
- `month`: month of data in this row
- `day`: day of data in this row
- `hour`: hour of data in this row
- `PM2.5`: PM2.5 concentration (ug/m^3)
- `PM10`: PM10 concentration (ug/m^3)
- `SO2`: SO2 concentration (ug/m^3)
- `NO2`: NO2 concentration (ug/m^3)
- `CO`: CO concentration (ug/m^3)
- `O3`: O3 concentration (ug/m^3)
- `TEMP`: temperature (degree Celsius)
- `PRES`: pressure (hPa)
- `DEWP`: dew point temperature (degree Celsius)
- `RAIN`: precipitation (mm)
- `wd`: wind direction
- `WSPM`: wind speed (m/s)
- `station`: name of the air-quality monitoring site <br>


Throughout this project, our attention will be solely directed to the `PM2.5 `feature. PM2.5 stands for particles with a diameter smaller than 2.5 micrometers, which is over 10 times thinner than a human hair—quite intriguing, isn't it? These particles emerge from burning fuel and chemical reactions in the atmosphere, be it coal in a power plant or gasoline in your car. Remarkably tiny, they have the potential to penetrate deep into the lungs and bloodstream, posing a gradual threat to your body over time.

## Methodologies, Techniques & Model

## Recommendation, conclusion, limitations

## Folder structure.
