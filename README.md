# Gang violence between online and offline
This project explores the causal pathways and magnitude between digital activity (e.g., social media platforms like Facebook) and real-world gang-related crimes. To model these dynamics, we use a bivariate Hawkes process, a type of point process that captures both the direction and magnitude of spillover effects between online and offline gang activities.

- The code generates synthetic data to simulate these interactions, allowing users to customize key parameters such as the number of gangs and the time window of interest for studying these dynamics. 

- A detailed analysis using real data from Chicago is presented in our published paper: "Measuring Online–Offline Spillover of Gang Violence Using Bivariate Hawkes Processes."
https://link.springer.com/article/10.1007/s10940-024-09592-5.

- The parameter estimation is done using the probabilistic software Stan, which can be installed very easily using pip or conda. 


