[**Home**](https://am-msba.github.io/Portfolio/) | [**Machine Learning Prediction Model**](https://am-msba.github.io/Machine_Learning_Prediction_Project/) |

### Background

This project addresses the Facility Location Problem (FLP), a strategic decision-making challenge in supply chain management. The goal was to determine the optimal location for factories to minimize the total cost of facility setup and transportation while satisfying all customer demands.

<p align="center">
  <img src="assets/Model-Setup.png" width="400" alt="Model Setup">
  <br>
  <i>Figure 1: Model components and requirements.</i>
</p>

---

### Methods and Tools

I developed a custom optimization solver in Python using a Mixed-Integer Programming (MIP) framework and applied it to an internally generated data set. The optimizer uses opening costs and customer distances to evaluate what factory locations should be opened as well as what customers should be designated to the open factories. The decision variables and constraints for the model are shown below:


<p align="center">
  <img src="assets/Distance-Matrix.png" width="400" alt="Distance Matrix">
  <br>
  <i>Figure 2: Sample distance matrix.</i>
</p>

<p align="center">
  <img src="assets/Factory-Costs.png" width="400" alt="Factory Costs">
  <br>
  <i>Figure 3: Factory Opening Costs.</i>
</p>

---

### Findings
The best solution for the problem is shown below:

<p align="center">
  <img src="assets/Optimization-Solution.png" width="350" alt="Optimization Solution">
  <br>
  <i>Figure 4: Optimization Solution.</i>
</p>

<p align="center">
  <img src="assets/Map-Viz.png" width="300" alt="Solution Map">
  <br>
  <i>Figure 5: Solution Map Visualization.</i>
</p>
