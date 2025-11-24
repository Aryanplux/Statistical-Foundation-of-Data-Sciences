# Monthly Mean Sunspot Number – Cycle Analysis & Visualization

## Overview

This project explores the long-term monthly mean total sunspot number, spanning January 1749 to November 2018.  
It demonstrates how to process public solar activity data, model the solar cycles, visualize distributions, analyze rolling trends (MNMC), apply a gamma distribution for periodic cycles, and detect peak solar activity periods.

---

## Assignment Steps

1. **Plot sunspot data over years**  
   Visualize the temporal trend and distribution, revealing the cyclical nature of solar activity.
2. **Model cycles with gamma distribution (reset every 12 years)**  
   Fit a gamma probability model for each ~11-year solar cycle segment.
3. **Histogram of counts**  
   Display the overall frequency distribution of monthly sunspot numbers.
4. **MNMC/groups analysis**  
   Plot rolling means for first 50 months, all samples, and last 50 months.
5. **Trace visualization & burn-out simulation**  
   Show moving averages (window a=4, b=10), drop out some values, and plot histograms of traces.
6. **Peak prediction**  
   Use rolling maxima and peak detection to predict the timing of sunspot cycle peaks.

---

## Data Source

- **Dataset:** [Monthly mean total sunspot number - SN_m_tot_V2.0.csv](https://www.sidc.be/SILSO/DATA/SN_m_tot_V2.0.csv)
- **Provider:** Royal Observatory of Belgium – Solar Influences Data Analysis Center (SIDC)
- **Variables:** Year, Month, FracDate, SunspotNum, StdDev, ObsNum, Definitive

---

## Technologies & Libraries

| Library      | Purpose                                   |
|--------------|-------------------------------------------|
| pandas       | Data loading, manipulation, statistics    |
| numpy        | Numerical computation                     |
| matplotlib   | Line, histogram, and trend plotting       |
| seaborn      | Heatmap and enhanced plotting             |
| scipy.stats  | Gamma distribution fitting                |
| scipy.signal | Peak detection for cycle timing           |

---

## How to Run

1. Download or clone the repository.
2. Download `SN_m_tot_V2.0.csv` into your working directory ([link](https://www.sidc.be/SILSO/DATA/SN_m_tot_V2.0.csv)).
3. Open and run the Jupyter notebook:  
   `MonthlySunspotAnalysis.ipynb`
4. All steps are annotated; outputs are visualized in-cell.

---

## Results

- Data shows pronounced ~11-year cycles in sunspot activity.
- Gamma fitting effectively models fluctuations per cycle segment.
- Rolling traces and burn-out simulation illustrate variability and gaps.
- Peak detection identifies major sunspot cycle peaks for scientific prediction.

---

## Project Structure
/
├── MonthlySunspotAnalysis.ipynb # Main analysis notebook
├── SN_m_tot_V2.0.csv # Sunspot dataset (download from SIDC)
├── images/ # Visualizations and plots
├── README.md # This documentation


---

## References

- [SIDC Sunspot Data](https://www.sidc.be/SILSO/DATA/SN_m_tot_V2.0.csv)
- [Gamma Distribution in Python (scipy.stats.gamma)](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.gamma.html)
- [Peak Detection (scipy.signal.find_peaks)](https://docs.scipy.org/doc/scipy/reference/generated/scipy.signal.find_peaks.html)

---

## Author

Aryan Dhiman  
CSU1658 – Statistical Foundation of Data Sciences  
Shoolini University

---

## License

MIT License — For academic and educational use

---

*Star this repo if you found it helpful!*

