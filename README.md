# Solar-Terrestrial-Coupling-Analysis: Sunspots vs Extreme Events

## Description
This project explores the statistical correlation between Solar Photospheric Activity (Sunspots) and Space Weather Events (Flares, CMEs, and Geomagnetic Storms) recorded during the rising phase of Solar Cycle 25.

## Objective
To quantify the relationship between sunspot number and the frequency of extreme solar and geomagnetic events during the rising phase of Solar Cycle 25, and evaluate whether sunspots can be used as a predictive proxy for space weather activity.

## Scientific Background
The high intensity of magnetic activity in certain regions of the solar photosphere inhibit plasma to undergo convection. These regions are primary sites for the storage of magnetic energy. When these magnetic fields undergo reconnection, they trigger high-energy phenomena such as Solar Flares and Coronal Mass Ejections (CMEs).

Analyzing the "Sunspot Number (R)" alongside event frequency allows us to visualize the Sun's magnetic "pulse" as it approaches the Solar Maximum.

## Methodology
- Data sources:
  - Daily Total Sunspot Number (SILSO/SIDC, Royal Observatory of Belgium)
  - Space Weather Event Data (NASA, via Kaggle)

## Results
The analysis reveals a strong positive correlation between sunspot number and the frequency of solar and geomagnetic events, particularly during periods of rapid increase in solar activity. Peaks in event frequency tend to align with increases in sunspot counts, supporting the hypothesis that sunspot regions act as indicators of stored magnetic energy and subsequent energetic releases.

## Limitations
- Temporal aggregation (monthly averages) may smooth short-term variations
- No lag analysis was performed to detect delayed Earth impacts

## Visualization
![Sunspots_X_SolarEvents](src/sunspots_x_solarevents.png)

## Technologies Used
- Python
- Matplotlib
- CSV data processing
