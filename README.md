# IPL Analysis Using Power BI

## Overview

This project involves analyzing Indian Premier League (IPL) cricket data using Power BI. The goal is to gain insights into team and player performances, match outcomes, and key metrics related to both batting and bowling. The analysis is carried out using data from multiple related tables, providing an in-depth view of IPL statistics and trends.

## Project Objective

The main objective of this project is to analyze IPL data to derive insights into various aspects of the game. This includes assessing the performance of players and teams, understanding match outcomes, and exploring key metrics related to batting and bowling. The ultimate goal is to identify the top 11 players based on the analysis.

## Datasets Used

The project uses the following datasets:

- **Fact Bowling:**
  - `match_id`: Unique identifier for the match.
  - `bowlingTeam`, `bowlerName`, `overs`, `maiden`, `runs`, `wickets`, `economy`, `0s`, `4s`, `6s`, `wides`, `noBalls`: Metrics related to bowling performance.

- **Fact Batting Summary:**
  - `match_id`, `teamInnings`, `battingPos`, `batsmanName`, `out/not_out`, `runs`, `balls`, `4s`, `6s`, `SR`: Metrics related to batting performance.

- **Dim Player:**
  - `name`, `team`, `battingStyle`, `bowlingStyle`, `playingRole`: Player-specific details.

- **Dim Match Summary:**
  - `team1`, `team2`, `winner`, `margin`, `matchDate`, `match_id`: Match-specific details.

## Power BI Dashboards

The project includes several interactive dashboards created using Power BI, which allow users to explore the IPL data and extract meaningful insights. The dashboards feature:

1. **Area Chart:** Displaying batting average, strike rate, boundary percentage, and average balls faced.
2. **Scatter Chart:** Illustrating the relationship between strike rate and batting average.
3. **Navigation Buttons:** Including Anchor, Finisher, Power Hitter, All Rounders, and Specialist Fast Bowler, which navigate to respective detailed pages.

## Key Insights and Findings

The analysis highlights:

- **Top 3 Finishers**
- **Top 3 All-Rounders**
- **Top 4 Fast Bowlers**
- **Final 11 Players:**
  1. Jos Buttler
  2. Rilee Rossouw
  3. Virat Kohli
  4. Surya Kumar Yadav
  5. Glenn Philiphs
  6. Marcus Stoinis
  7. Sikandar Raza
  8. Shadab Khan
  9. Sam Curran
  10. Shaheen Shah Afridi
  11. Anrich Nortje

These insights provide a comprehensive view of the IPL, offering valuable information for fans, analysts, and stakeholders.

## Conclusion

The IPL Analysis project demonstrates the power of data analytics and visualization in understanding sports performance. By leveraging the capabilities of Power BI, the project uncovers insights that can inform strategy, marketing, and fan engagement. The dashboards serve as a powerful tool for exploring IPL's rich history and statistics.

## How to Run the Project

### Prerequisites

To run this project, you will need:

- Power BI Desktop installed on your computer.
- Basic understanding of Power BI and data visualization concepts.

### Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/ipl-analysis-powerbi.git
   ```
2. Open the Power BI Desktop application.

3. Open the `.pbix` file provided in the repository.

### Usage

- Use the interactive slicers and filters within the Power BI dashboards to explore different aspects of the IPL data.
- Navigate through the Anchor, Finisher, Power Hitter, All Rounders, and Specialist Fast Bowler buttons to explore detailed pages.
- Customize the visuals as per your needs to gain more specific insights.
- You can also connect the Power BI file to your data source if you wish to analyze a different dataset.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please feel free to open an issue or submit a pull request.

## Contact

- **Author:** Aditya Jatav
- **Email:** [Aditya-Mail](mailto:adityajatav19072004@gmail.com)
- **LinkedIn:** [Aditya Jatav](https://www.linkedin.com/in/aditya-jatav)