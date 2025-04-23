This notebook implements a **continuous model updating framework** for plant fungal disease spread dynamics using **Maximum Likelihood Estimation (MLE)** on streaming data. The model captures both deterministic and stochastic behaviours of (primary and secondary) infections, leveraging the Gillespie algorithm to simulate realistic demographic variability.  

#### **Key Features**  
- **Stochastic vs. Deterministic Modeling**: Simulates disease spread using Gillespie’s stochastic algorithm and compares results to deterministic ODE predictions.  
- **Real-Time Parameter Updates**: Uses MLE to efficiently update model parameters as new data streams in, avoiding computationally expensive Bayesian methods.  
- **Visualization**: Generates plots of infection trajectories, confidence intervals, and average behaviour to highlight differences between stochastic and deterministic dynamics.  
- **Epidemiological Insights**: Designed for scenarios like pathogen outbreaks, with customizable parameters (e.g., infection rates, host susceptibility decay).  

#### **Technical Components**  
- **Python-based**: `matplotlib` for visualization, and `numpy` for numerical analysis.  
- **Modular Code**: Easily extendable to other dynamical systems.   

#### **Use Cases**  
- Researchers studying **epidemiological dynamics** or **biological systems**.  
- Proof of concept for real-time monitoring and forecasting of disease spread in streaming data environments.  
- Educational tool for teaching stochastic modeling and parameter estimation.  

