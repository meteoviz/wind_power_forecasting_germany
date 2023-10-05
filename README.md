## Wind power forecasting in Germany: A machine learning approach
### Using tree-based models and feature engineering for accurate one-step ahead forecasts

This is the Python code repository for my data science project and complements the project report (Projektarbeit) submitted on October 4, 2023. The four-month-long 'Certified Data Scientist' course was administered by Digethic: Digital Business School and ran from the start of June, 2023 to the end of September, 2023.

All Jupyter code notebooks can be found in the top-level directory called `notebooks`. They are numbered according to their chronological significance, even though the code was written non-linearly. At the top of each notebook I provide a list of main ideas covered to aid navigation. 

Regarding the code, I did not intend to write the most performant code as this wasn't a priority. I also did not reformat or optimise code before making this repo public. There are, however, many comments throughout to aid understanding. These were mainly intended to aid my own understanding, but now also serve as an aid for others. 

Also note that I created a unique time series dataset for this project by combining multiple datasets and engineering many new features. The original datasets were not pushed to the repo due to their large size. Therefore, the `data` directory is empty. I did, however, push the updated versions of my combined time series dataset to the `data_to_push` directory as pickle files of the pandas DataFrame. The final and most recent version is called `df_main_smard_era5_final_reordered.pkl`. 
