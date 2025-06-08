# Urban-energy-footprint-simulator
Urban Energy Footprint Simulator models Hyderabad’s residential, commercial, and street lighting energy demand using real city boundaries and simulated data. Includes interactive maps and scenario analysis for urban growth and solar adoption to explore sustainable urban energy futures. Built with Python and GeoPandas.
# Urban Energy Footprint Simulator – Hyderabad

This project is a beginner-friendly Python Jupyter Notebook that simulates and visualizes urban energy demand across Hyderabad, India. It models **residential, commercial, and public lighting energy consumption** at a spatial level using real city boundaries and synthetic proxy data. It also includes a scenario simulator to explore impacts of urban growth and rooftop solar adoption.

---

## Features

- **Hyderabad boundary extraction** from OpenStreetMap using `OSMnx`.
- **Grid-based zoning** inside the city for spatial analysis.
- **Simulated population, commercial area, and road length** data to proxy energy demand.
- Calculation of **residential, commercial, and street lighting energy consumption**.
- Visualization of energy demand using static maps (`matplotlib`) and interactive maps (`Folium`).
- **Scenario simulator** to test the effects of population growth and solar energy offset.

---

## Technologies & Libraries

- Python 3.x
- Jupyter Notebook
- `geopandas`, `osmnx`, `folium`, `matplotlib`, `pandas`, `shapely`

---

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/urban-energy-footprint-simulator.git
   cd urban-energy-footprint-simulator/notebooks

2. Install required libraries:
   pip install -r requirements.txt

3. Run the notebook energy_simulator_hyderabad.ipynb in Jupyter:
   jupyter notebook energy_simulator_hyderabad.ipynb

4. Explore the sections:

Data setup and boundary download
Zone creation and population simulation
Multi-sector energy demand estimation
Interactive maps
Scenario simulations for urban growth and solar adoption

# Project Structure

urban-energy-footprint-simulator/
├── data/                     # Datasets (city boundary, simulated data)
├── notebooks/
│   └── energy_simulator_hyderabad.ipynb
├── README.md
├── requirements.txt

# Future Work

Integrate real population and land use datasets (e.g., WorldPop, Bhuvan).
Add building footprint and road network extraction for accurate commercial and lighting demand.
Develop interactive widgets for real-time scenario simulation.
Incorporate energy supply-side models, including renewable energy potential.
Extend to other Indian cities.

# References

OpenStreetMap
OSMnx Python Library
BEE India Energy Reports
WorldPop Population Data

