[**Home**](https://am-msba.github.io/Portfolio/) | 

### Background

This project addresses the Facility Location Problem (FLP), a strategic decision-making challenge in supply chain management. The goal was to determine the optimal location for factories to minimize the total cost of facility setup and transportation while satisfying all customer demands.

![Model Setup](assets/Model-Setup.png)

### Methods and Tools

I developed a custom optimization solver in Python using a Mixed-Integer Programming (MIP) framework and applied it to an internally generated data set. The optimizer uses opening costs and customer distances to evaluate what factory locations should be opened as well as what customers should be designated to the open factories. The decision variables and constraints for the model are shown below:

![Model Setup](assets/Distance-Matrix.png)
![Model Setup](assets/Factory-Costs.png)

### Findings
The best solution for the problem is shown below:

![Model Setup](assets/Map-Viz.png)
![Model Setup](assets/Optimization-Solution.png)
