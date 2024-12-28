**How to run?**

**STEPS:**

Clone the repository

Project repo: https://github.com/

**STEP 01**- 
#Create a conda environment after opening the repository

conda create -p venv python==3.10 -y

conda activate #the created environment

**STEP 02**- 
#install the requirements

pip install -r requirements.txt

**STEP 03** - 
Create a .env file in the root directory and add your Google Gemini credentials as follows:

GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"

**STEP 04** -
#Finally run the following command

streamlit run vision.py

Now,

open up localhost:
