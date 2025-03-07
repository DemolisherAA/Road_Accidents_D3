# Road_Accidents_D3
The tree diagram and connecting timeline presents the number of road accidents in the Australian state of Victoria over five years (2018-2022). Accident count is shown per day of the week, over three speed group categories: 50km/ph and under, 60-90km/ph and 100km/ph and over.

# Road Accidents Data Visualization

This repository contains a data visualization project focused on road accidents in Victoria, Australia, over five years (2018-2022). The project presents accident counts categorized by day of the week and speed zones using D3.js and interactive visualizations.

---

## Contents

### Files in the Repository:

1. **`Road_Accidents_Victoria_D3.html`**
   - Provides the main visualization built using D3.js.
   - Displays a tree diagram and timeline connecting road accident data.
   - Interactive features include highlighting and tooltips for nodes and bars.

2. **`accident_data.csv`**
   - Contains the raw data for road accidents, including speed zones, days of the week, and accident counts.

3. **`roads_hierarchy.json`**
   - Defines the hierarchy for speed zones and years, forming the tree structure used in the visualization.

4. **`color-legend.js`**
   - Implements a reusable color legend for encoding accident counts in the visualization.

5. **`README.md`**
   - Documentation explaining the project, its contents, and usage instructions.

6. **`LICENSE`**
   - Specifies the open-source license under which this project is distributed.

---

## Visualization Details

- **Tree Diagram**:
  - Represents accident data hierarchically, categorized by speed zones and years.
  - Nodes are color-coded and interactive, showing additional details on hover.

- **Timeline**:
  - Connects the tree diagram to daily accident counts, offering a detailed view for each day of the week.
  - Encodes accident counts using a color scale for better understanding.

---

## Setup and Usage

### Prerequisites
- A modern web browser supporting JavaScript and D3.js.
- A local server or hosting platform to render `Road_Accidents_Victoria_D3.html`.

### Steps to Run:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Road_Accidents_D3.git
   ```
2. Open `Road_Accidents_Victoria_D3.html` in a browser to view the visualization.

---

## Data Source

- The data is sourced from the [Victoria Road Crash Data](https://discover.data.vic.gov.au/dataset/victoria-road-crash-data).
- All accidents missing speed zone data or containing codes 777, 888, and 999 were excluded.

---

## Contributions

Contributions to improve this visualization are welcome! Fork the repository and submit a pull request for any enhancements.

---

## License

This project is licensed under GNU (General Public License).
