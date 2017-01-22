This project runs with Anaconda for Python 2.7 and is implmented in an iPython Notebook

- The project needs the data to be in the following location:
	- /Documents/seizure_data/
- Inside this directory, place the following provided files (it is fine to copy all provided files into this location but only these are necessary):
	- patient_1_inter_labeled_features.csv
	- patient_1_preic_labeled_features.csv
 	- patient_1_unlabeled_features.csv
	- patient_2_inter_labeled_features.csv
	- patient_2_preic_labeled_features.csv
	- patient_2_unlabeled_features.csv
	- patient_3_inter_labeled_features.csv
	- patient_3_preic_labeled_features.csv
	- patient_3_unlabeled_features.csv
- If the Kaggle data is available (no longer on Kaggle website), inside the above directory also place the following:
	- test_1_new
	- test_2_new
	- test_3_new
	- train_1
	- train_2
	- train_3
	- train_and_test_data_labels_safe.csv
	- Inside train_1, train_2, and train_3, create and empty folder for each called unsafe, and execute all cells in notebook.

- From Jupyter Notebook, open seizure.ipynb
- If the original Kaggle Data is not available, run the first code cell inside the notebook then continue from section 2.1 in the notebook to execute rest of project.
- To submit to Kaggle for score, execute section 5.0 of project and submit file output.csv generated in above directory.