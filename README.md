# IPL Match Batting Intent Analysis

## Project Overview
This project delves into an in-depth analysis of batting performance in a T20 IPL cricket match (RCB vs. DC, 2025). Using ball-by-ball data, we derive meaningful insights into batting intent, phase-specific performance, and match-winning strategies. The primary goal is to assess key metrics such as strike rate, boundary percentage, and dot ball rate, providing a clear view of player performance and game dynamics.

## Objectives
1. **Analyze Player Performance**: Evaluate individual players' contributions based on strike rate, boundary percentage, and dot ball rate.
2. **Phase-Specific Insights**: Understand how batting strategies evolve across different game phases (Powerplay, Middle Overs, Death Overs).
3. **Visualizations**: Provide clear, engaging visual representations of the data for easy interpretation.

## Key Features
- **Comprehensive Data Analysis**: Processes ball-by-ball data to extract critical metrics.
- **Phase Segmentation**: Breaks down match analysis into distinct phases (Powerplay, Middle Overs, Death Overs).
- **Metrics Calculations**:
  - **Strike Rate**: Measures batting efficiency.
  - **Boundary Percentage**: Highlights aggressive scoring.
  - **Dot Ball Rate**: Identifies strike rotation effectiveness.
- **Interactive Visualizations**:
  - Runs scored per over.
  - Boundary count by batter.
  - Dot ball rate comparisons.
  - Phase-wise strike rate and radial charts.

## Technologies Used
- **Python**: Core language for data manipulation and analysis.
- **Pandas**: For data cleaning and preprocessing.
- **Seaborn and Matplotlib**: For creating detailed visualizations.
- **Jupyter Notebook**: Interactive environment for code execution and visualization.

## Dataset
- **Source**: IPL match ball-by-ball dataset (`ipl_match_1473461_deliveries.csv`).
- **Key Columns**:
  - `team`: Batting team.
  - `over`: Over number.
  - `batter`: Player name.
  - `runs_batter`: Runs scored by the batter on each delivery.
  - `wicket_kind`: Type of dismissal (if applicable).

## How It Works
1. **Data Loading**: Reads the ball-by-ball CSV data into a pandas DataFrame.
2. **Data Cleaning**: Handles missing values and prepares derived columns for analysis (e.g., boundary, dot ball flags).
3. **Metrics Calculation**:
   - **Strike Rate** = (Total Runs / Balls Faced) × 100
   - **Boundary Percentage** = (Boundaries / Balls Faced) × 100
   - **Dot Ball Rate** = (Dot Balls / Balls Faced) × 100
4. **Phase Analysis**: Segments the data into Powerplay (1–6 overs), Middle Overs (7–15), and Death Overs (16–20).
5. **Visualizations**: Creates insightful plots for understanding batting performance.

## Visual Outputs
- **Runs Scored per Over**: A bar plot illustrating the total runs scored in each over.
- **Boundary Count by Batter**: Highlights aggressive players through a bar chart.
- **Dot Ball Rate by Batter**: Boxplot showing strike rotation efficiency.
- **Phase-Wise Strike Rate**: Line graph comparing batting aggression across game phases.
- **Radial Chart**: Circular visualization of phase-wise strike rate.

## Key Insights
- **Strike Rate Trends**: Higher strike rates observed in Death Overs compared to Powerplay or Middle Overs.
- **Boundary Contributions**: Specific batters dominated boundary scoring, emphasizing their role in the team’s success.
- **Dot Ball Analysis**: Identifies players who effectively minimized dot balls, ensuring consistent scoring pressure.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ipl-analysis
   ```
2. Navigate to the project directory:
   ```bash
   cd ipl-analysis
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Future Enhancements
- **Bowling Analysis**: Extend insights to bowlers' performance.
- **Win Prediction Models**: Incorporate machine learning to predict match outcomes.
- **Real-Time Analysis**: Adapt code for real-time match data.



