# Peterbilt Cost Optimization through Predictive Analytics
## The Mission: Cracking the Warranty Cost Code 🕵️‍♂️

Every truck rolling off the Peterbilt assembly line represents not just engineering excellence, but a potential future cost in the form of warranty claims. My mission was to act as a data detective, analyzing years of vehicle data to uncover a central business mystery: which specific vehicle attributes and combinations were driving up warranty costs? By solving this puzzle, we could help Peterbilt make smarter decisions, build better trucks, and protect their bottom line.

##🧠 The Data-Driven Blueprint

This project was a deep dive into two proprietary datasets from Peterbilt Motor Company. My goal was to create a clear, actionable roadmap for reducing warranty costs. Here is the process I followed:

Data Analysis: I first performed a multivariate analysis to uncover which vehicle attributes were most correlated with high warranty costs. This foundational step was crucial for identifying initial patterns.

Predictive Modeling: Using XGBoost, a powerful machine learning model, I built a predictive engine that could identify truck configurations likely to result in high-cost claims.

Model Interpretation: I used SHAP (SHapley Additive exPlanations) to interpret the model's predictions. This allowed me to explain exactly which attributes were driving the costs, turning the model into a transparent and powerful business tool.

## Modeling
 
This project addresses a critical business problem for Peterbilt Motor Company by using predictive analytics to optimize product quality. By analyzing vehicle attributes and warranty claim data, the goal was to identify which truck configurations were driving up costs.




Models	Accuracy	Precision	Recall
Decision Tree	74%	67%	73%
Random Forest	80%	85%	75%
LightGBM	87%	92%	82%
CatBoost	87%	91%	83%
XGBoost	88%	92%	83%

A powerful XGBoost model was built to predict high-cost claims. We then used SHAP to interpret the model's decisions, uncovering specific attributes and their combinations that were most responsible for the increased warranty expenses.

The analysis provided a clear roadmap for cost reduction, pinpointing where Peterbilt could focus its quality control efforts. This not only helps them save money but also improves product reliability, leading to increased customer satisfaction.

## The Big Reveal: Cracking the Warranty Cost Code 🕵️‍♂️
This project wasn't just about crunching numbers; it was about giving Peterbilt a clear roadmap to a more profitable future. We went from a complex business problem to simple, actionable insights.

## Key Findings & The "Aha!" Moments ✨
Our analysis revealed the true culprits behind high warranty costs. We found that specific attributes, especially 

Attributes 6, 7, and 2, were major drivers of expense. The real "aha!" moment came from discovering that some attribute pairs, like 

Attributes 6 and 7, have a negative synergy—they interact in ways that significantly amplify claims. This points to a potential compatibility issue that could be fixed with targeted design changes.

## The Final Word: Turning Data into Dollars 💰
By understanding these relationships, Peterbilt can do more than just react to problems; they can proactively prevent them. The insights from this project provide a strategic guide to:

Optimize truck configurations to avoid high-risk attribute combinations.

Target quality control efforts where they matter most.


Enhance customer trust by offering reliable, high-quality products.

# In short, we turned data into dollars, giving Peterbilt a powerful tool for a profitable, data-driven future.



