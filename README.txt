# DeepCap-NAI: accurate identification of influenza neuraminidase inhibitors based on capsule network
Capsule network deep learning methods to predict influenza neuraminidase inhibitors.

## File description
The features file contains the features descriptor used in this study

### Files in /model:
model.h5: 

### Dependencies
pip install Tensorflow/
pip install keras
pip install scikit-learn
!pip install rdkit-pypi
!pip install jpype1


### Step 1: 
Prepare an influenza neuraminidase inhibitor (SMILES) that needs to be predicted in .csv format.
### Step 2: 
Extract the features from the SMILES using descriptor.ipynb file. 
### Step 3: 
try python test_model.ipynb to test the extracted features as influenza neuraminidase inhibitor or not.
### Step 4: 
Output: \
The prediction results are summarized in the file "prediction.csv".



echo "# DeepCap-NAI" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/saeed344/DeepCap-NAI.git
git push -u origin main

