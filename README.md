

# **Titanic Dataset Analysis**

This repository contains an analysis of the **Titanic dataset**, a classic dataset used for data exploration and machine learning.
The goal of this project was to analyze the dataset, answer specific questions, and derive insights about the passengers aboard the Titanic.

---

## **Dataset Overview**
The Titanic dataset contains information about the passengers aboard the RMS Titanic, including:
- **PassengerId**: Unique identifier for each passenger.
- **Survived**: Survival status (0 = No, 1 = Yes).
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
- **Name**: Passenger name.
- **Sex**: Gender of the passenger.
- **Age**: Age in years.
- **SibSp**: Number of siblings/spouses aboard.
- **Parch**: Number of parents/children aboard.
- **Ticket**: Ticket number.
- **Fare**: Passenger fare.
- **Cabin**: Cabin number.
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

---

## **Analysis Questions**
The analysis focused on answering the following questions:
1. What was the overall survival rate?
2. Did gender play a role in survival?
3. How did passenger class (Pclass) affect survival?
4. What was the distribution of ages among passengers?
5. Did passengers with family members (SibSp/Parch) have a higher chance of survival?
6. How did the fare correlate with survival?

---

## **Tools Used**
- **Python**: Primary programming language.
- **Libraries**:
  - Pandas (data manipulation)
  - NumPy (numerical computations)
  - Matplotlib and Seaborn (data visualization)
  - Scikit-learn (machine learning, if applicable)
- **Jupyter Notebook**: For interactive analysis and visualization.

---

## **Key Insights**
1. **Survival Rate**: Approximately 38% of passengers survived.
2. **Gender Impact**: Women had a significantly higher survival rate than men.
3. **Passenger Class**: 1st-class passengers had the highest survival rate, while 3rd-class passengers had the lowest.
4. **Age Distribution**: Most passengers were between 20 and 40 years old.
5. **Family Size**: Passengers with 1-3 family members had a higher survival rate.
6. **Fare Correlation**: Higher fares were associated with higher survival rates.

---

## **Files in the Repository**
- `titanic_analysis.ipynb`: Jupyter Notebook containing the full analysis.
- `titanic.csv`: The dataset used for the analysis.
- `README.md`: This file.
- (Optional) `requirements.txt`: List of Python dependencies.

---

## **How to Run the Code**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/titanic-analysis.git
   cd titanic-analysis
   ```

2. Install dependencies (if needed):
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook titanic_analysis.ipynb
   ```

---

## **Contributing**
Contributions are welcome! If you have suggestions or improvements:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push and open a pull request.


Explore the data and insights in the notebook! 🚢📊
