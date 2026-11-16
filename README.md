# County Rainfall and Planting Advisory

## Project Summary

This project analyses monthly rainfall data from five Kenyan counties: Nairobi, Nakuru, Kisumu, Mombasa and Machakos. Using Python and NumPy, the analysis cleans invalid rainfall readings, calculates annual rainfall totals, identifies wettest months and dry months, and determines the best consecutive two-month rainfall windows for planting. The results are exported into a CSV file to support an NGO in providing data-driven planting guidance to farmers.

## How to Run

Open the analysis notebook in Google Colab:

[Open rainfall_analysis.ipynb in Google Colab](https://colab.research.google.com/github/YOUR-GITHUB-USERNAME/plp-da-a2-rainfall-advisory/blob/main/rainfall_analysis.ipynb)

Replace `YOUR-GITHUB-USERNAME` with your actual GitHub username.

## Planting Advisory

- Nairobi, Nakuru, Kisumu and Mombasa have April–May as their recommended two-month rainfall windows, with combined rainfall of 395 mm, 265 mm, 420 mm and 390 mm respectively.
- Machakos has November–December as its recommended planting window, with 278 mm of combined rainfall, and requires additional attention because it recorded six dry months.
- These recommendations are based on historical rainfall patterns, and farmers should also consider soil moisture, crop requirements and weather forecasts before planting.

## Project Files

- `rainfall_analysis.ipynb` – Data cleaning, NumPy analysis and planting recommendations.
- `rainfall_summary.csv` – County-level rainfall analysis results.
- `requirements.txt` – Required Python library dependencies.

## Technologies Used

- Python
- NumPy
- CSV module
- Google Colab
- GitHub
