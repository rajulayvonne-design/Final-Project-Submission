# Aviation Investment De-Risking: A Strategic Fleet Acquisition Analysis

---

## 1. Project Overview

This project provides a data-driven risk assessment of various aircraft makes and models using historical aviation accident data. The primary goal is to determine the **lowest-risk aircraft** for a company expanding its portfolio into commercial and private aviation enterprises.

The findings are translated into actionable recommendations for the Head of the new Aviation Division, guiding strategic purchasing and operational planning.

**Analyst:** Yvonne Rajula

---

## 2. Business Problem Statement

A company is diversifying its portfolio by entering the aviation industry (commercial and private enterprises) but lacks internal expertise on aircraft risk.

The objective is to analyze historical accident and incident data to:
1.  Identify aircraft manufacturers (**Make**) and specific **Models** that demonstrate the highest historical reliability (lowest accident frequency).
2.  Provide concrete, data-backed recommendations on which aircraft to **purchase** and which operational periods require increased **caution**.

---

## 3. Data and Methodology

### Data Source
The analysis utilizes a comprehensive dataset of historical aviation accidents and incidents, containing over 90,000 unique event records.

### Data Preparation
Key data preparation steps included:
* **Deduplication** of identical accident reports.
* **Imputation:** Missing numerical fields, such as 'Total Fatal Injuries' and 'Number of Engines,' were handled by filling in the gaps using the **mean (average)** value. This technique ensured the dataset remained robust for statistical analysis.

### Risk Metric
The primary metric for risk assessment was **Total Accident Count** (Accident Frequency) for manufacturers, models, and temporal periods.

---

## 4. Key Findings and Recommendations

The analysis led to three core recommendations for de-risking the new aviation venture:

### Recommendation 1: Prioritize Reliable Manufacturers
| Finding | Recommendation |
| :--- | :--- |
| **Boeing** aircraft show a comparatively high degree of historical reliability and efficiency, having a lower overall accident count in the dataset. | **PRIORITIZE** models from manufacturers like **Boeing** for the commercial fleet. |
| **Cessna** aircraft, particularly smaller models, are associated with a significantly higher total number of accidents. | **SCRUTINIZE or AVOID** the purchase of **Cessna** aircraft to minimize initial risk exposure. |

### Recommendation 2: Focus on Low-Risk Models for Private Use
| Finding | Recommendation |
| :--- | :--- |
| The **Piper PA-28-180** model exhibits high reliability, having one of the lowest accident counts in the entire dataset. | **RECOMMEND** the **Piper PA-28-180** as a primary option for the private enterprise fleet. |
| The **Cessna 152** and **Cessna 172** models had the highest accident counts. | Place high-risk models like the **Cessna 152** and **Cessna 172** on a **restricted purchase list**. |

### Recommendation 3: Implement Seasonal Safety Protocols
| Finding | Recommendation |
| :--- | :--- |
| Accident frequencies show a distinct **seasonal peak during the Summer months** (June, July, August), likely due to increased flight volume. | Implement **enhanced operational caution, safety briefings, and maintenance oversight** protocols specifically during the high-risk summer season. |

---

## 5. Notebook Structure

The analysis is fully documented in `student.ipynb`, which follows the below structure:

* **Business Problem Statement:** Defines the project goal.
* **Data Cleaning & Preprocessing:** Handles missing values and data type conversion.
* **Exploratory Data Analysis (EDA):** Visualizations and analysis of accidents by Make, Model, and Time (Month).
* **Conclusion & Recommendation:** Summarizes the actionable insights.