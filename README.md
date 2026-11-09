# ANA500-Airline-Delay-and-Satisfaction
ANA500 analysis of airline arrival delays and passenger satisfaction using regression, cross-validation, and neural networks.

# Airline Arrival Delays and Passenger Satisfaction

This ANA500 project examines whether flight distance improves arrival-delay estimates after accounting for departure delay, and how arrival delay relates to passenger satisfaction.

The [Jupyter notebook](Airline_Arrival_Delays_Satisfaction_Micro_Project.ipynb) contains the complete analysis: data preparation, visualizations, model comparisons, results, and interpretation.

## Key findings

- Departure delay was the strongest predictor of arrival delay. Flight distance added little practical improvement in the models tested.
- In the matched test comparison, linear models had lower average absolute error than the neural networks.
- Delayed passengers reported lower satisfaction. Using the same five predictors and test records, the satisfaction neural network achieved a test ROC AUC of 0.867, compared with 0.846 for logistic regression.

These satisfaction findings describe associations, not causal effects. Models using arrival delay or survey service ratings should not be treated as preflight predictions.

## Data

The analysis uses a course-provided airline dataset. The dataset is not included here, but the notebook retains its saved outputs for review.
