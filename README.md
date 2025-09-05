# -Location-Based-Machine-Learning-for-Predicting-High-Risk-Infection-Areas-
Built a spatial clustering model using DBSCAN to detect high-risk infection zones from geotagged health data. Visualized risk areas with interactive Folium maps, enabling real-time public health decisions. Combined unsupervised learning with geospatial analysis for actionable insights.


Spatial Clustering of High-Risk Infection Zones
📌 Project Overview

This project applies DBSCAN clustering on geotagged health data to identify and visualize high-risk infection zones. By combining unsupervised learning with geospatial data, the model provides actionable insights for public health decision-making.

🚀 Features

Detects clusters of infection using DBSCAN

Visualizes risk areas with interactive maps (Folium)

Processes geotagged health data with Pandas & GeoPandas

Supports real-time decision making through geospatial insights

🛠️ Tech Stack

Python

Scikit-learn (DBSCAN)

Pandas

GeoPandas

Folium

📂 Project Structure
├── data/              # Sample or input geotagged health dataset
├── notebooks/         # Jupyter notebooks for model training & visualization
├── src/               # Python scripts for preprocessing & clustering
├── results/           # Generated maps and outputs
└── README.md          # Project documentation

⚙️ Installation
# Clone this repository
git clone https://github.com/your-username/infection-zone-clustering.git
cd infection-zone-clustering

# Install dependencies
pip install -r requirements.txt

▶️ Usage
# Run clustering and visualization
python src/main.py


Open the generated HTML map file in your browser to explore infection zones.

📊 Example Output

Interactive map highlighting clusters of infection risk zones.

Heatmaps and cluster boundaries for better understanding of spread patterns.

🔮 Future Enhancements

Integration with real-time health APIs

Support for time-series trend analysis

Deployment as a dashboard (Streamlit / Dash)

🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.
