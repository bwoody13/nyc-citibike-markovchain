# NYC CitiBike Analysis
Analysis of NYC CitiBike stations using a Markov Chain to determine the number of available bikes at a given station

## Approach
- Cleaned and prepared the data, performing some high-level overview and analysis with Pandas
- Selected 3 stations that had heavy traffic and were hypothesized to show different trends
- Formatted each as a discrete Markov Chain, splitting into 10-minute intervals as transitions and categorizing into morning and evening
- Based upon counting transitions of in-flows and out-flows of each station, determined the transition probabilities
- Built the transition matrices for each station and then found the stationary distributions
- Observed and analyzed the trends for each station and at each time of day
