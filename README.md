MSc Data Science Major Research Project
Felix Li

Instructions for Using this Code Repository:

1. Make sure all main files are within the same directory. Main files are:
    a) mrp_main_fl.ipynb (for data exploration and initial cleaning) 
    b) mrp_model.ipynb (for training the model and subsequent cleaning)
    c) mrp_predict_lime.ipynb (for calculating LIME values and exporting dashboard data)
    d) OPTIONAL: mrp_model_new_course.ipynb (for testing the model on task-independent training/test sets)
    e) grades_data.json (from the dataset)
    f) programming_data.json (from the dataset)

2. Install prerequisite packages

3. Run mrp_main_fl.ipynb

4. Run mrp.model (optionally mrp_model_new_course)

5. Run mrp_predict_lime
    a) be aware that lime value calculation on all tasks take a significant amount of time and RAM. It may be necessary to break the parquet file down into smaller chunks based on specific tasks to prevent crashes.

6. The resulting lime_values.parquet file can be used for dashboarding/analytics