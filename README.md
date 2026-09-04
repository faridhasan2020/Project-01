This is a USA_Housing Analysis Project
Different Regression has been done to find out appropriate result.

▶ Project title and overview:
This is a project of USA House price prediction.

▶ Dataset description:
The data set is clean and have no duplication.

▶ Model comparison table with all trained models:
												
Model name	Validation MSE	Validation R square	Training MSE	Train R square	Test MSE	Test R square	Best K	Degree	Best Degree	Best Alpha	Best MSE	
Linear Regression	10,435,054,798.00	0.9102	10,292,121,830.71	0.9189	9,804,414,953.31	0.9222						
Polynomial Regression	10,738,690,273.52	0.9076	10,321,092,615.97									
Ridge	10,984,151,943.32	0.9055						10	2	1	10,447,906,606.53	
Lesso									2	10	10,447,423,235.35	
KNN	15,819,687,755.00	0.853			15,329,416,786.00	0.878	15				15,819,687,755.00	
												

▶ Final model details: name, R2, MSE, and why it was chosen:
Linear Regression was selected as the final model because it achieved the highest validation R² (0.9102) among the evaluated models. Its training R² of 0.9189 and validation R² of 0.9102 have a small gap of 0.0087, indicating little evidence of overfitting. After locking the model based on validation performance, it was evaluated once on the held-out test set. The final Test R² was 0.9222 and Test MSE was approximately 9.80 billion. The test set was not used for model selection or hyperparameter tuning.															


▶ Screenshots of the Gradio interface:

▶ Public Hugging Face Space URL, if deployed (optional):

▶ Installation instructions:
Please check the requirements.txt file for installation.
git clone [your-repo-url]
cd house-price-prediction
pip install -r requirements.txt

▶ How to run the project:
