## COVID 19 Vaccination Site Optimization
# Overview
* This project aims to address the challenge of selecting optimal vaccination site locations in response to the COVID-19 pandemic. 
* It explores methods to ensure equitable distribution of vaccines by determining the most suitable sites based on population density, COVID-19 cases, and accessibility.
# Motivation:
* The COVID-19 pandemic required rapid and efficient vaccination efforts, particularly in densely populated urban areas. 
* This project focuses on optimizing vaccination site locations to improve access for the population, minimize travel distances, and ensure maximum vaccine coverage.

# Goal:
* This project concentrates on solving the problem on two different levels,
that is, a relatively small area (Municipal level) and a relatively large area
(Mass level).

# Methodology:
* <mark> Municipal Level </mark>: A mathematical model is developed to optimize vaccination site locations based on population density and COVID-19 cases,
  with the goal of minimizing travel distance and maximizing accessibility.
* <mark> Mass Level </mark>: A five-step approach using Entropy Weighting Method (EWM) and Multiple Attribute Utility Theory (MAUT) for ranking potential vaccination sites.
* <mark> Tools Used </mark> : Geographic Information System (GIS), OSMNX for road distance computation, and Genetic Algorithms for optimization.

# Results:
* The project identifies optimal vaccination site locations based on different scenarios (1 to 4 sites), demonstrating how geographic distribution affects vaccination access. Sites located near high population density and COVID-19 cases tend to be the most effective.
[Roadmap Of San Juan Showing the optimal location of L = 1(top left), L = 2(top right), L=3(bottom left), L= 4(bottom right) vaccination sites](<img width="485" alt="Screenshot 2024-10-21 at 12 50 24 AM" src="https://github.com/user-attachments/assets/b1a1fcb0-f877-4892-910b-5d31e1ef7af4">)

# Technologies & Tools:
* Python (OSMNX, Genetic Algorithms)
* GIS Software for spatial analysis
* Entropy Weighting Method and Multiple Attribute Utility Theory for decision-making

# Conclusion: 
* The proposed method effectively selects vaccination sites to maximize vaccine accessibility and minimize travel distances, which can be applied to municipalities and larger urban areas.The use of algorithms like Genetic Algorithm makes the solution scalable for larger datasets.
# Future Work:
* This methodology can be extended to optimize site selection for other public health interventions, such as disease treatment centers or drug distribution sites.
# References
1) [Optimal selection of COVID-19 vaccination sites in the Philippines at the municipal level](https://peerj.com/articles/14151/)
2) [A mass vaccination site selection problem: An application of GIS and
entropy-based MAUT approach ](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9212444/pdf/main.pdf)
3) [Google Colab File](https://colab.research.google.com/drive/1VAh7c3XRqm8qbFu_zFm4ZDQ8GZaO0aT-?
usp=sharing)
