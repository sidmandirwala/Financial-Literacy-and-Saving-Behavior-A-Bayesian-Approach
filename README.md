# Financial Literacy and Saving Behavior: A Bayesian Approach

This project investigates how **financial literacy** mediates the relationship between **age** and **saving behavior** using Bayesian causal analysis. The analysis employs statistical modeling, data preprocessing, and posterior inference to extract meaningful insights.

## Project Overview
1. **Primary Question**: How does financial literacy mediate the relationship between age and saving behavior?
2. **Data**: A dataset containing demographic information, financial literacy levels, and saving behavior of students.
3. **Key Findings**:
   - Financial literacy is a critical driver of saving behavior.
   - Age indirectly influences saving behavior through its impact on financial literacy.

## Features and Methods
### 1. Data Preprocessing
- Removed unnecessary columns.
- Handled income data and financial aid attributes.

### 2. Causal Model
- Developed a Directed Acyclic Graph (DAG) to establish causal relationships:
  - **Age → Financial Literacy → Saving Behavior**

### 3. Statistical Analysis
- Built Bayesian mediation models using **PyMC** for:
  - Financial literacy as a function of age.
  - Saving behavior as a function of financial literacy.
- Posterior inference performed to evaluate the models.

### 4. Diagnostics
- Trace plots and posterior predictive checks ensured model reliability and convergence.

## Key Libraries Used
- **PyMC** for Bayesian modeling.
- **ArviZ** for visualization and diagnostics.
- **NetworkX** for causal graph representation.

## Insights and Future Work
### Insights
- Age indirectly affects saving behavior through financial literacy.
- Financial literacy strongly correlates with saving tendencies, regardless of age.

### Future Directions
- Incorporate additional confounders for robust causal inference.
- Expand to include longitudinal data for temporal effects.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/sidmandirwala/Financial-Literacy-and-Saving-Behavior-A-Bayesian-Approach.git
    ```
    
2. Install Dependencies
    ```bash
    pip install -r requirements.txt
    ```

3. Execute the Jupyter Notebook
    ```bash
    jupyter notebook Project.ipynb
    ```
