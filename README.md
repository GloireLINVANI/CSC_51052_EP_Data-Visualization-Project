# CSC_51052_EP_Data-Visualization-Project

## Project Description

This project focuses on football match analysis using data visualization techniques. The visualizations provide insights into match-level events, player performance, and team statistics. Using web-based technologies like HTML, CSS, and JavaScript, combined with D3.js, we created an interactive platform to explore football data dynamically.

The visualizations include:

1. **Match Visualization**: Displays goals in matches, incorporating player positions, ball movements, and Voronoi diagrams.
2. **Player Statistics**: Analyzes individual player performances with detailed metrics.
3. **Team Statistics**: Highlights team performance metrics, comparing home and away teams.

The primary interface for the project is the `index.html` file, which acts as the main entry point for the visualizations. The visualizations can be run locally using a modern web browser.

---

## File Structure

Below is the file structure of the project:

```
CSC_51052_EP_Data-Visualization-Project/
├── data/
│   ├── events/                   # Event data for matches
│   ├── logos/                    # Team logos
│   ├── matches/                  # Match data files
│   ├── matches_to_visualize/     # Configurations for matches to visualize
│   ├── spec/                     # Additional specifications
│   └── competitions.json         # Competition details
├── js/
│   ├── custom-d3-soccer.min.js   # Customized d3-soccer library
│   ├── d3.v7.min.js              # D3.js version 7 library
│   ├── globalcode.js             # JavaScript program for main page
│   ├── match_stat.js             # Match statistics implementation
│   ├── match_viz.js              # Match visualization implementation
│   └── part2.js                  # Player statistics implementation
├── index.html                    # Main entry point for the project
├── match_stat_style.css          # Styles for match statistics
├── match_viz.html                # Match visualization page
├── match_viz_styles.css          # Styles for match visualization
├── style.css                     # General styles for the project
└── README.md                     # Project description and instructions
```

---

## Running the Project

To run the visualizations locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/GloireLINVANI/CSC_51052_EP_Data-Visualization-Project.git
   cd CSC_51052_EP_Data-Visualization-Project
   ```

2. Open the `index.html` file in a modern web browser (e.g., Chrome, Firefox, Safari). This file serves as the main page for accessing the visualizations.

---

## Dataset

This project utilizes two datasets:

1. **StatsBomb Open Data**: Provides detailed match-level, player-level, and team-level statistics.

   - [StatsBomb Open Data Repository](https://github.com/statsbomb/open-data)

2. **Last Row Tracking Data**: Contains tracking data for specific goals scored by Liverpool FC in 2019 and a few other matches.
   - [Last Row Tracking Data Repository](https://github.com/Friends-of-Tracking-Data-FoTD/Last-Row)

These datasets are processed to generate visualizations that provide meaningful insights into football matches.

---

## Authors

This project was collaboratively developed by:

- **Gloire LINVANI, École Polytechnique, Télécom Paris, France**: Match Visualization
- **Yann MILLET, École Polytechnique, Télécom Paris, France**: Player Statistics, Game Selection Menu
- **Yong MOK, École Polytechnique, France**: Team Statistics
