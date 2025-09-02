# Resume_Job_Matcher (Stop)
This is a new and unfinished project aimed at matching resumes to the most suitable job offers based on the job description using a semantic similarity model.

---

# Step 1: Import Dataset
- The "Resume and job_description" dataset is gain from Kaggle platform. (https://www.kaggle.com/datasets/pranavvenugo/resume-and-job-description）

# Step 2: Data Understanding
- Check data type
- Check data shape
- Display the first five row
- Check missing data
- Check duplicate data
- Check resume & job description length

# Step 3: Apply Sentence-Transformer Model
- In this step main goals is to calculate the similarities of each resume to each diffrent job description.
- The similarity higher than 0.8 will be label as match. Else will be not match.
- The step to apply the sentence-transformer model is：
  1) Install and import necessary libraries
  2) Initialize the sentence-transformer model
  3) Encode the resume and job description
  4) Calculate the cosine similarity
  5) Filter the match and not match result based on the similarity value.

# Step 4: Evaluation
- This step is to evalute the similarity result to ensure the dataset quality.

# Step 5: Dowload Dataset
- This step will dowload the dataset which will be ready to build machine learning or deep learning model.
