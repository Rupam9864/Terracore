
#AI-Powered Bio-Inspired Environmental Monitoring System-inspired by Plant Roots, Ant Colonies and Bee Behaviour

***"Smarter Farms. Greener Planet."***





## Overview
This project is a low-cost real-time environmental monitoring system for small-scale farmers. The system uses bio-inspired sensors and AI models to detect soil moisture, nutrient levels, temperature, humidity, and pest infestations. It then provides actionable insights via simulated SMS alerts.

<img src="/images/Icon.png" alt="Terracore Icon" style="width : 100px ; height : 100px; " />





## Problem Statement

Small-scale farmers face significant challenges:
- **Unpredictable Weather & Pest Outbreaks:** Crop losses due to drought, pest infestations, and other adverse conditions.
- **Limited Access to Technology:** Many farmers do not have smartphones or reliable internet access.
- **Economic Hardship:** Inability to make proactive decisions leads to reduced yields and financial stress.

Terracore addresses these issues by democratizing agricultural intelligence and delivering crucial, data-driven insights in a format accessible to all.

---

## Our Solution

### Key Features:
- **AI-Powered Crop Monitoring:**  
  Utilize bio-inspired sensors to continuously monitor soil moisture, nutrient levels, temperature, humidity, and pest presence.
  
- **Irrigation Intelligence:**  
  Forecast soil moisture levels to reduce water waste and optimize irrigation.

- **Crop Stress Detection:**  
  Early identification of drought and pest risks to enable timely action.

- **SMS Alert System:**  
  Provide actionable recommendations via SMS in local languages, ensuring accessibility for all farmers.

- **Holistic, Low-Cost Design:**  
  Integrates multiple sensors and AI analysis into a single, affordable unit that operates offline.


<img src="/images/Architecture.png" alt="Architecture icon" />







### Bio-Mimicry Inspiration:
Our sensor design is inspired by natural systems:
- **Plant Roots:** Mimic how roots efficiently absorb water and nutrients, guiding our soil moisture and nutrient sensors.
- **Ant Colonies:** Emulate the decentralized, rapid response mechanisms of ant swarms for pest detection.
- **Bee Behavior:** Draw inspiration from bees for optimal temperature and humidity sensing, much like bees regulate their hives.
  
These bio-mimetic principles ensure that the system is not only innovative but also practical and efficient in monitoring environmental conditions in a manner akin to nature.

### MVP Highlights:
- 3D prototype of the Terracore AI unit.
- Real-time visualization dashboard.
- Integrated SMS alert system.
- Bio-inspired sensor technology for comprehensive monitoring.

<img src="/images/MVP.png" alt="Terracore Icon" style="width : 100px ; height : 100px; " />

---







## Repository Structure

Terracore/ ├── .gitignore ├── LICENSE ├── README.md ├── requirements.txt ├── main.py └── Agronomic_Thresholds_Documentation.md

## Acknowledgements

Research & Inspiration: Ideas inspired by studies from Nature, ScienceDirect, World Bank blogs, and various agritech research sources.

Community Support: https://asknature.org/

## Contributing

Contributions are welcome! To contribute:

1) Fork the repository.
2) Create a new branch for your feature or bug fix.
3) Submit a pull request with a clear description of your changes.
4) For major changes, please open an issue first to discuss what you would like to change. Please adhere to this project's `code of conduct`.
## Technology Used 

1) Python
2) NumPy & Pandas: For numerical operations and data manipulation.
3) scikit-learn: For machine learning and model evaluation.
4) Matplotlib: For data visualization.
5) pickle: For model persistence.
## Technical Details

1) Data Generation: Synthetic sensor data is created to simulate real-world environmental conditions (e.g., soil moisture, temperature). Risk labels are assigned using simple, rule-based logic.

2) Model: A Decision Tree classifier is used for its simplicity and interpretability, making it ideal for low-resource settings.

3) Evaluation: The model's performance is evaluated with metrics like accuracy, classification reports, and confusion matrices.

4) Visualization: The distribution of risk levels is visualized using matplotlib to ensure balanced data.

5) Offline Operation: The model is serialized with pickle for offline use, ensuring that it can run on minimal hardware without internet dependency.
## Installation

**Clone the Repository:**
   ```bash
   git clone https://github.com/Rupam9864/Terracore.git
    
