# 📊 PhonePe Pulse Analytics Dashboard

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://python.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-Dashboard-FF4B4B.svg)](https://streamlit.io)
[![Plotly](https://img.shields.io/badge/Plotly-Interactive-3D9970.svg)](https://plotly.com)

> An interactive multi-page analytics dashboard built with Streamlit to visualize 
> PhonePe Pulse data across India — covering digital transactions, insurance adoption, 
> and registered user trends with India choropleth maps.

---

## 🖥️ Live Demo
> 🚀 [View Live Dashboard](https://your-app.streamlit.app) ← Deploy on Streamlit Cloud (free!)

---
## 📸 Dashboard Preview

### 💳 Transactions Dashboard
| India Transaction Map |
|---|
| ![Transactions Map](screenshots/01_transactions_india_map.png) |

### 🛡️ Insurance Dashboard
| Insurance KPI Overview | Insurance Type Distribution | Insurance Map |
|---|---|---|
| ![Insurance KPI](screenshots/02_insurance_overview_kpi.png) | ![Insurance Pie](screenshots/03_insurance_type_pie.png) | ![Insurance Map](screenshots/04_insurance_india_map.png) |

### 👥 Users Dashboard
| Users Overview | State-wise Registered Users |
|---|---|
| ![Users Overview](screenshots/05_users_overview_donut.png) | ![Users Bar](screenshots/06_users_statewise_bar.png) |

---

## 🎯 Key Features

- **Transactions Dashboard** — KPI cards, state-wise analysis, transaction type distribution, India choropleth map
- **Insurance Dashboard** — Insurance amount analysis, type distribution, state-wise map
- **Users Dashboard** — Registered user trends, state-wise user map, growth insights
- **Dynamic Filters** — Filter by state, year, and quarter across all dashboards
- **India Choropleth Maps** — Built with Plotly Express + GeoJSON for geo-visualizations

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core programming |
| Streamlit | Web dashboard framework |
| Pandas | Data processing & analysis |
| Plotly Express | Interactive charts & maps |
| GeoJSON | India state boundary maps |

---

## 📁 Project Structure
phonepe-pulse-dashboard/
├── dashboards.py          # Main multi-page Streamlit app
├── main.py                # Entry point / app launcher
├── agg_transaction.csv    # Aggregated transactions data
├── agg_insurence.csv      # Aggregated insurance data
├── agg_user.csv           # Aggregated user data
├── screenshots/           # Dashboard preview images
├── requirements.txt       # Python dependencies
└── README.md
---

## ⚙️ Installation & Run

```bash
# Clone the repo
git clone https://github.com/bsaiteja447/phonepe-pulse-dashboard.git
cd phonepe-pulse-dashboard

# Install dependencies
pip install -r requirements.txt

# Run the dashboard
streamlit run dashboards.py
```

---

## 📊 Data Source

Data sourced from [PhonePe Pulse](https://github.com/PhonePe/pulse) — India's digital payment public dataset covering transactions, insurance, and user metrics across all Indian states from 2018–2024.

---

## 💡 Key Insights Uncovered

- Maharashtra, Karnataka, and Telangana lead in digital transaction volumes
- Insurance adoption is highest in southern states
- User growth shows consistent YoY increase post-2020 with UPI adoption surge

---

## 👤 Author

**B. Sai Teja** — Data Analyst | Python • SQL • Power BI  
📧 bsaiteja562@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/bsaiteja447) | [GitHub](https://github.com/bsaiteja447)
