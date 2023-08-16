# Resume Categorization

### Steps:
  1. If possible create a virtual environment in python.
  2. Then inside the virtual environment clone the github repo.
  3. Use the requirement.txt to install the dependencies.
  4. **PLEASE download the model** : https://mega.nz/file/Eq0jATbJ#LEmoVJzASIgJ_T88UjRAO9q9H1QK7DzxhPYYYwkWtWA
  5. Put the model in the same directory as scripts.py **(Makse sure the name of model is "bert_model.h5")**
  6. I was not able to upload the model due to its huge size.
  7. Run script.py from the command line as intended : python script.py "directory". Make sure you are in the same directory as script.py
  8. resume-categorization (2).ipynb contains the model training and documentation guide.

#### Creating Virtual Environment:
Go to the directory you want to clone the repo. 
Open command line on that directory.

  ``` command-line
pip install venv
python -m venv "name of virtual environment"
git clone https://github.com/abdullahmoosa/resume-categorization-final.git
cd resume-catogirization-final
pip install -r requirements.txt
```

#### Running the script:
After installing requirement.txt. 
```
python script.py path_to_directory_containing_the_resume_pdfs
```

Here replace 'path_to_directory_containing_the_resume_pdfs' with the actual directory containing the pdfs.


### Important Findings:
  1. BERT performs the best.
  2. The dataset is imbalanced. Therefore the accuracy is not good for some classes.
  3. **For further details please review "resume-categorization (2).ipynb" .**
     
