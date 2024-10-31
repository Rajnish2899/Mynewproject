# GitHub Users in Moscow

- This repository contains data about GitHub users in Moscow with over 50 followers, including details of their public repositories.
- Analyzing the data revealed that several popular repositories are primarily written in JavaScript and Python, indicating strong interest in web and data-focused projects.
- Developers targeting Moscow-based users might focus on creating tools or resources that support web and data science projects.

## Files

1. `users.csv`: Contains information about GitHub users in Moscow with over 50 followers.
2. `repositories.csv`: Contains information about public repositories from these users.
3. `gitscrap.py`: Python script used to collect this data.

## Data Collection

- Data was collected using the GitHub API, gathering user details and repository information for users located in Moscow.
- The data collection was performed on {time.strftime('%Y-%m-%d')}.
- Only included users with 50+ followers and up to 500 most recently pushed repositories per user.
