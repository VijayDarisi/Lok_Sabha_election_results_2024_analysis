# Lok_Sabha_election_results_2024_analysis

## Project Overview
This project on election results data can be used to analyze the performance of different political parties across several states. The dataset contains information on the number of seats won by each party, the total number of seats available in each state, the seat share percentage, and the classification of parties as either national or regional

## Dataset

The dataset (`Loksabha_results_of_all_states.csv`) contains the following columns:

- `Party`: Name of the political party.
- `State`: Name of the state.
- `Won`: Number of seats won by the party in the state.
- `Total`: Total number of seats available in the state.
- `Seat_Share_Percentage`: Percentage of seats won by the party in the state.
- `Party_Type`: Indicates whether the party is national or regional.

### Data Source

The dataset was obtained from the [Election Commission of India's results page](https://results.eci.gov.in) using web scraping techniques.

## Visualization Insights

1. **State-Wise Seat Distribution**: Visualizes the distribution of seats across different states and union territories.
2. **Top 10 Winning Parties in this Election**: Highlights the top 10 parties with the highest number of seats won.
3. **State-Wise Seat Distribution with Party Names**: Shows the seat distribution in each state with corresponding party names.
4. **Performance of National vs Regional Parties**: Compares the performance of national and regional parties in terms of seats won.
5. **Party-Wise Seat Wins over Multiple States**: Visualizes the seat wins of parties across multiple states.
6. **Performance of Parties in Major States**: Analyzes the performance of parties in key states.
7. **Average Number of Seats Won per State by Party**: Displays the average number of seats won by each party in different states.
8. **Distribution of Seat Share Percentage**: Shows the distribution of seat share percentages among different parties.

### Additional Insights
9. **Swing Seats (Seats Won with < 5% Margin)**: Identifies seats that were won with a margin of less than 5%.
10. **Regional Dominance of National Parties**: Highlights the regional dominance of national parties in various states.

### Prerequisites

Ensure you have the following installed:
- Python 3.7 or later
- Pandas
- Matplotlib
- Seaborn
- Requests
- BeautifulSoup


## Conclusion

This project provides a detailed analysis of election results, showing important performance metrics and trends for different political parties across states. The insights from this analysis can be used for further political research .




