# monte-carlo-pi-project
# Monte Carlo Estimation of π

## Project Overview

This project demonstrates how the Monte Carlo method can be used to estimate the value of the mathematical constant $\pi$.

The Monte Carlo method is a probabilistic algorithm that uses random sampling to approximate numerical results.

In this project we simulate random points inside a square and determine how many fall inside a unit circle. Using the ratio between these values we approximate the value of $\pi$.

---

## Mathematical Idea

The Monte Carlo estimator for $\pi$ is based on the ratio between the area of a circle and the area of a square.

Area of circle:

$$
A = \pi r^2
$$

For a unit circle:

$$
A = \pi
$$

Area of square:

$$
A = 4
$$

Therefore:

$$
\pi \approx 4 \times \frac{N_c}{N}
$$

Where:

- $N$ = total generated points  
- $N_c$ = points inside the circle  

---

## Implementation

The project is implemented in **Python** using a **Jupyter Notebook**.

Main steps of the algorithm:

1. Generate random points inside the square [-1,1] × [-1,1]
2. Check if the point lies inside the unit circle
3. Count points inside the circle
4. Estimate $\pi$ using the Monte Carlo formula
5. Visualize the simulation using matplotlib

---

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Matplotlib

---

## Repository Structure

```
monte-carlo-pi-project
│
├── monte_carlo_pi.ipynb # main notebook with implementation
├── README.md # project description
└── requirements.txt # required Python libraries
```

---

## Author

Fantaz24  
Student project for "Math Concepts for Developers" course.
