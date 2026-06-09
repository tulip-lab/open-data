# ISF-TDF2023

## Dataset Information

| Field | Value |
| --- | --- |
| **Title** | ISF-TDF2023 |
| **Type** | Dataset |
| **Language** | English |
| **License** |  |
| **Data Status** | Static |
| **Update Frequency** | No |
| **Date Published** | 2026-05-20 |
| **Date Updated** | 2026-06-02 |
| **Portal** | https://github.com/tulip-lab/open-data |
| **URL** | https://github.com/tulip-lab/open-data/tree/master/ISF-TDF2023 |
| **Publisher** | TULIP Lab |
| **Point of Contact** | Prof. Gang Li |

## Overview

The **ISF-TDF2023** dataset contains monthly Chinese outbound tourism demand data for **20 selected destination countries/regions**. The dataset was developed for the **Tourism Demand Forecasting Competition 2024** hosed by 45th International Symposium on Forecasting Conference and includes historical observations together with designated validation and evaluation periods extending to **July 2024**.

The data span multiple tourism market regimes, including the pre-pandemic period, the COVID-19 disruption period, and the post-pandemic recovery phase, providing a challenging benchmark for tourism demand forecasting under significant structural changes and demand shocks.

## Data Structure

Each destination country/region is represented by containing a continuous monthly tourism demand series. The complete timeline is divided into the following periods:

| Period | Description |
|----------|-------------|
| Earliest Available Date – December 2019 | Pre-COVID tourism demand period |
| March 2020 – June 2022 | COVID-19 disruption period |
| July 2022 – February 2023 | Early recovery period |
| March 2023 – July 2023 | Validation period |
| August 2023 – July 2024 | Competition evaluation period |

### Historical Period

The historical observations include:

- **Pre-COVID period:** Earliest available date to December 2019
- **COVID-19 disruption period:** March 2020 to June 2022
- **Early recovery period:** July 2022 to February 2023

These periods capture substantial structural changes in international tourism demand and provide valuable information for model development. Some of the country has missing values and some imputation or processing is requried.

### Validation Period

The period from **March 2023 to July 2023** serves as the **validation period**. Participants may use this segment to:

- Develop forecasting models
- Tune model hyperparameters
- Compare forecasting approaches
- Assess model performance during the initial recovery phase

### Evaluation Period

The period from **August 2023 to July 2024** serves as the **official evaluation period** of the competition. Forecast accuracy during this horizon is used for the final assessment and ranking of forecasting models.


## ISF-TDF2023 Evaluation Metric

Forecasting performance in the **ISF-TDF2023** dataset is evaluated using the **Mean Absolute Scaled Error (MASE)**, a scale-independent forecasting accuracy measure that enables fair comparisons across destinations with substantially different tourism demand volumes.

Unlike percentage-based metrics, MASE remains robust when actual observations contain very small values or zeros, which are common in tourism demand series affected by major disruptions such as the COVID-19 pandemic. As a result, MASE is particularly suitable for evaluating forecasting performance across heterogeneous tourism markets and periods characterized by structural changes.

The MASE is defined as:

\[
\text{MASE} =
\frac{\frac{1}{n}\sum_{t=1}^{n}\left|y_t-\hat{y}_t\right|}
{\frac{1}{T-m}\sum_{t=m+1}^{T}\left|y_t-y_{t-m}\right|}
\]

where:

- \(y_t\) denotes the observed tourism demand;
- \(\hat{y}_t\) denotes the forecast value;
- \(m\) represents the seasonal period;
- \(T\) denotes the length of the training series;
- \(n\) denotes the number of observations in the forecasting horizon.

The denominator corresponds to the mean absolute error of a **seasonal naïve benchmark model** estimated from the historical training data. Consequently, MASE measures forecasting accuracy relative to a simple benchmark forecast.

### Interpretation

| MASE Value | Interpretation |
|------------|----------------|
| MASE < 1 | Forecasting model performs better than the seasonal naïve benchmark |
| MASE = 1 | Forecasting model performs similarly to the benchmark |
| MASE > 1 | Forecasting model performs worse than the benchmark |

### Competition Ranking

For the **ISF-TDF2023** dataset, model rankings are determined based on the **average MASE** computed over the **evaluation period (August 2023 – July 2024)** across all destination series.

Lower MASE values indicate better forecasting performance and higher ranking positions.

### Why MASE?

MASE is adopted as the official evaluation metric because it:

- Is scale-independent and comparable across destinations with different demand levels;
- Remains well-defined when actual observations contain zeros or near-zero values;
- Provides a meaningful comparison against a seasonal naïve benchmark;
- Is widely used in forecasting competitions and tourism demand forecasting research;
- Is particularly suitable for datasets containing structural breaks and post-pandemic recovery dynamics.

## Notes

The dataset intentionally covers multiple tourism market regimes, including pre-pandemic, pandemic, recovery, validation, and evaluation periods. These regime shifts create substantial forecasting challenges and provide a realistic benchmark for assessing model robustness, adaptability, and generalization performance.

## Citation

If you use this dataset in academic research, please cite the corresponding Competition2024 dataset and associated publications from TULIP Lab.

* Yishuo Zhang, Baobao Song, Xin Li, Rob Law, and Gang Li (2026). [Imputation recovery tourism demand forecasting.](https://doi.org/10.1016/j.tourman.2020.104100). **Annals of Tourism Research**, Vol 118, Feb 2026.


`BibTex` information:

    @article{zhang2026imputation,
    title={Imputation recovery tourism demand forecasting},
    author={Zhang, Yishuo and Song, Baobao and Li, Xin and Law, Rob and Li, Gang},
    journal={Annals of Tourism Research},
    volume={118},
    pages={104144},
    year={2026},
    publisher={Elsevier}
}

## Disclaimer

This dataset was collected, compiled, and processed in support of the **45th International Symposium on Forecasting (ISF 2025)** forecasting competition and related research activities. The dataset is provided solely for research, educational, and benchmarking purposes. While reasonable efforts have been made to ensure the accuracy and quality of the data, the publisher makes no warranties regarding its completeness, correctness, or fitness for any particular purpose. All intellectual property rights related to the original data sources remain with their respective owners. The inclusion of data in this repository does not imply any transfer of ownership rights.

If you are the owner of any data source included in this dataset and have concerns regarding its use, distribution, copyright, licensing, privacy, or other related matters, please contact the dataset owner. Upon verification of the request, the relevant data will be reviewed and, where appropriate, removed or updated in a timely manner.

## Contact

**TULIP Lab**

- Website: https://www.tulip.academy/
- GitHub: https://github.com/tuliplab
- Contact: Prof. Gang Li



