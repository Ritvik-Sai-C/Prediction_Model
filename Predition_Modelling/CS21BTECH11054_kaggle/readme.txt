Kaggle Hackathon

Kaggle Score:
The sub_kaggle_FOML code achieved a Kaggle score of Public score: 0.74237 and Private score: 0.50533 on the leaderboard.
The second highest Kaggle score was of Public score: 0.73777 and Private score: 0.50809 on the leaderboard.


Team:
CS21BTECH11054_CS21BTECH11040

Team Members:
Ritvik Sai C (CS21BTECH11054)
Nishanth Bhoomi (CS21BTECH11040)


Kaggle Username - ritviksaichippa
CS21BTECH11054 (Representative)

Code Description:

File Structure:
test_output.csv: Final submission files.
sub_kaggle_FOML.ipynb: Jupyter Notebook containing the code.

Libraries Used:
Pandas
Scikit-Learn
Seaborn
Matplotlib

Code Execution:

Environment Setup:
Ensure you have Python and Jupyter Notebook installed.
Install required libraries using the following command:
pip install pandas scikit-learn seaborn matplotlib

Code Execution:
Open the Jupyter Notebook iith_foml_2023_predictions_best.ipynb.
Run each cell in sequential order to reproduce the results.

Data Files:
Ensure that the following files are in the same directory as the notebook:
iith_foml_2023_train.csv: Training data.
test_input.csv: Test data.

Model Description:
The code prints out the correlaton matrix to find the features which are not needed.
Features specified in the rem_fea list were removed.
Missing values were filled with the mean of the respective columns.
Standard scaling was applied to the features.
The code uses a Gradient Boosting Classifier with hyperparameters tuned through GridSearchCV.



