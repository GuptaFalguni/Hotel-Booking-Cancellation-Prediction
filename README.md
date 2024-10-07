# Hotel-Booking-Cancellation-Prediction
The Hotel Booking Cancellation Prediction project uses machine learning to predict whether hotel bookings will be canceled. By analyzing customer and booking data, the model helps hotels anticipate cancellations, optimize resource management, and reduce revenue loss. The model, based on Random Forest, achieves 83% accuracy and is deployed via Gradio for real-time use, providing actionable insights to minimize cancellations and improve operational efficiency.

## Problem Statement
The INN Hotels Group is facing significant revenue loss and operational inefficiencies due to a rising number of booking cancellations, with an annual loss estimated at $0.25 million. Current heuristic-based methods have proven ineffective in predicting cancellations. The hotel group needs a data-driven solution to accurately predict booking cancellations, allowing them to proactively manage inventory, optimize resource allocation, and minimize revenue losses.

## Models and Techniques
The project utilizes several machine learning models to predict hotel booking cancellations. 

The models evaluated include:

- **Random Forest:** Achieved the best performance with 83% accuracy, 88% precision for non-cancellations, and 77% recall for cancellations.
- **Voting Classifier:** Combines multiple classifiers for improved accuracy.
- **XGBoost:** Gradient boosting model for handling complex patterns in the data.
- **Decision Tree:** Simple and interpretable, but less effective than ensemble methods.
- **Gradient Boosting and AdaBoost:** Boosting methods that improve weaker learners’ performance.
  
Techniques used:

- **Feature Engineering:** Encoding categorical variables, handling missing data, and scaling numerical features.
- **Model Evaluation:** Models were evaluated using accuracy, precision, recall, F1-score, and Cohen’s Kappa to ensure robust performance.
- **Deployment:** The final model (Random Forest) was deployed using Gradio for real-time predictions.

## Files Included
- **Hotel Cancellation Prediction.ipynb:** Contains data preprocessing, feature engineering, and model development.
- **Hotel Cancellation Deployment.ipynb:** Demonstrates how the final model is deployed using Gradio for real-time predictions.
- **Hotell_Cancellation_Model _Deployment_View.png:** A visual representation of the deployment view for the model.

## Conclusion
The Hotel Booking Cancellation Prediction project successfully addresses the challenge of predicting booking cancellations using a Random Forest model, which achieved 83% accuracy, 88% precision for non-cancellations, and 77% recall for cancellations. By deploying the model via Gradio, hotels can now make real-time predictions, allowing for better resource management and a reduction in revenue loss caused by cancellations. This data-driven approach provides a scalable and effective solution to optimize hotel operations and improve decision-making.




