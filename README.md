# BERN02_exam_performance
Predicting exam performance based on relevant features.

# Fair Principles

**Findable:** We have used a public dataset (https://www.kaggle.com/datasets/mobeenfatimah/student-exam-performance-and-success-dataset), last accessed 15.10.2026. Additionally, each student has their own unique student id. The ful project can be found in 'final_project.ipynb', however we did not obtain a DOI number for it. Within the notebook all variables present in the dataset are documented and put into 6 cathegories, as well as which columns were picked as target, identifier, leakage or redundant.
**Accessible:** The repository is publicly avaliable at https://github.com/or5722bo-s-design/BERN02_exam_performance, last accessed 17.10.2026, and can be read without any special tools. We do not redistribute the data, it is license protected and can be obtained from Kaggle at the url above, the file is titled 'student_exam_performance.csv'. To run the cells in notebook, place the csv file in the same folder as the notebook file, because it accesses it via DATA_PATH.
**Interoperable:** The data file is in csv format and we have used jupyter notebook, python, pandas, scikit-learn, scipy, seaborn etc. The names of the variables are descriptive and the type of each variable is detailed in the notebook. The preprocessing build a pipeline with scikit-learn, so it is reusable for other data if needed.
**Reproducable:** We have used a fixed random seed 42 for reproducability for the train test split and CV. All the choices for preprocessing are justified and documented in the notebook. The notebook also walks us through how the data has been changed or manipulated to be able to create the project. The required packages and versions are listed in 'eviroment.yml'. We have used a third-party data set that we did not collect by ourselves. The results that we have concluded refer to associations not causations. We can't verify the way the data was generated or sampled. 

# Authors

Linn Preuss and Orsolya Bosáková.