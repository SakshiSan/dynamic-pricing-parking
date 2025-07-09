# 🚗 Dynamic Pricing for Parking - Summer Analytics 2025

This repository contains two models that simulate dynamic pricing mechanisms for parking spaces using data-driven strategies.

---

## 📁 Files Included

| File Name                           | Description                                        |
|------------------------------------|----------------------------------------------------|
| Model1_Dynamic_Pricing_Project.ipynb  | Streaming-based price modeling using Pathway       |
| Model_2_Dynamic_Pricing_Final.ipynb   | Linear-based batch model for demand + price        |
| dataset.csv                          | Dataset used in both models                        |

---

## 🛠️ Tech Stack Used

- Python
- Google Colab
- Pandas
- Pathway
- Bokeh
- Panel

---

## 📌 Project Overview

- **Model 1:** Uses real-time streaming via Pathway to aggregate occupancy and calculate dynamic pricing.
- **Model 2:** Uses a linear formula for demand estimation followed by price computation.
- Both models visualize final price using interactive Bokeh plots.

---

## 📊 Architecture Diagram

You can copy this diagram into [Mermaid Live Editor](https://mermaid.live/edit) for better visualization.

```
graph TD
    A[dataset.csv] --> B[Data Preprocessing (Combine Date & Time)]
    B --> C[Feature Engineering (Traffic Encoding, VehicleType Mapping)]
    C --> D[Model 1 (Streaming: Pathway)]
    C --> E[Model 2 (Batch Linear Model)]
    D --> F[Final Price (Streamed)]
    E --> G[Final Price (Batch)]
    F --> H[Bokeh Visualization]
    G --> H
```

---

## 📂 Repository Structure

```
.
├── Model1_Dynamic_Pricing_Project.ipynb
├── Model_2_Dynamic_Pricing_Final.ipynb
├── dataset.csv
└── README.md
```

---

## 📥 How to Use

1. Clone the repository or open notebooks in Google Colab.
2. Ensure `dataset.csv` is present in the same directory.
3. Run each notebook step by step to visualize the pricing model.

---

## 📬 Contact

For any queries, raise an issue or contact [Your GitHub Username].