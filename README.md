# F1 Season Analysis: Max Verstappen 2025

This small project provides a data analysis and visualization of Max Verstappen's performance throughout the 2025 Formula 1 season. Using the FastF1 API, the Jupyter Notebook processes race data to generate a series of performance metrics and visualizations.

---

## Key Analyses & Visualizations

This notebook generates a comprehensive set of plots and statistical summaries to evaluate performance.

### 1. Telemetry Analysis (Per Race)
- **Fastest Lap Telemetry Chart:** A multi-panel plot displaying Speed, RPM, Gear, and DRS status throughout Verstappen's fastest lap for a selected Grand Prix.
- **Circuit Speed Map:** A visualization of the circuit layout where the track line is colored based on Verstappen's speed, using a 'plasma' colormap to highlight high and low-speed sections.

### 2. Season Performance Dashboard
A multi-panel dashboard summarizing the entire season's performance:

- **Points Evolution:** A line chart tracking the cumulative points scored by Verstappen race after race, with the area under the curve shaded.
- **Final Race Positions:** A horizontal bar chart showing the finishing position for each race, with gold, silver, and bronze colors for podium finishes.
- **Grid vs. Final Position:** A bar chart illustrating the number of positions gained or lost in each race compared to the starting grid position.
- **Detailed Season Statistics:** A text-based summary panel displaying key performance indicators like win rate, podium rate, average points, and DNF rate.

### 3. Consistency and Reliability Analysis
- **Podium Consistency Chart:** A pie chart that shows the percentage of races finished on the podium versus off the podium.
- **Comprehensive Statistical Report:** A detailed text output summarizing performance metrics, including:
    - Race Performance (Avg Finish, Best Finish)
    - Points Consistency (Avg Points, Std Dev)
    - Reliability & Success Rate (Win Rate, Podium Rate, DNF Rate)
