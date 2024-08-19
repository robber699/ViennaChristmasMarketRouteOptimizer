# Optimizing Christmas Market Visits in Vienna

This project aims to optimize the route for visiting as many Christmas markets in Vienna as possible within a day, considering various constraints such as market opening hours, visit durations, and travel times between markets. We utilized Google Maps API to extract travel times and employed heuristic approaches, including a greedy algorithm and Ant Colony Optimization, to generate efficient routes. The solution accommodates multiple days of visits, adjusting for factors like diminishing energy over time.

## Project Overview

With Christmas around the corner, the challenge is to visit the maximum number of Christmas markets in Vienna within a limited timeframe. Given the numerous markets, it’s impossible to visit all of them in one day. Therefore, this project focuses on optimizing the route under several constraints:
- Each market has different opening and closing times.
- A predefined amount of time (default 30 minutes) is spent at each market.
- The overall available time is limited by the earliest opening and latest closing time.
- Markets should only be visited once.

## Methodology

1. **Data Collection**: We used the Google Maps API to obtain travel times between markets by both walking and public transport.
2. **Heuristic Optimization**:
   - **Greedy Algorithm**: A simple approach to get a quick, suboptimal solution by always choosing the nearest market.
   - **Ant Colony Optimization**: A more sophisticated algorithm that simulates the behavior of ants to find optimal paths.

## Results

The optimized routes ensure that the maximum number of markets can be visited within the available time, balancing the constraints effectively. The project is designed to be flexible, allowing users to customize the duration of their visits and spread the route across multiple days if needed.

