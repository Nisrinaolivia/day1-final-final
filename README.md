1. Create README.md file for taking notes

## SAVING CODE
1. On the left hand side of the screen, go to "source control"
2. Click to add files to the commit (i.e., stage changes)
3. Enter a commit message (anything)
4. Click "Commit"
5. Click "Sync changes"
Check Github repository to confirm

## SETTING UP ENVIRONMENT (IN TERMINAL)
1. Create virtual environment
> python -n venv .venv
2. Activate virtual environment
> source .venv/bin/activate
3. To install libraries/dependencies, first create a requirements.txt file
4. add openai, streamlit, python-dotenv to requirements.txt file
5. Install dependencies by referring to requirements.txt file
>pip install -r requirements.txt
6. Create a .env file
7. ensure .env file is grayed out (git ignored) - if not, edit .gitignored to include .env
8. add secrets to .env
.OPENAI_API_KEY="<INSERT>"

##REMEMBER TO SYNC WITH GITHUB REPOSITORY

##CREATE SOME CODE
1. Create a python file = call it whatever you'd like -home.py by convention
2. run streamlit, referring to the python file I created
>streamlit run home.py

## CREATE CODE IN YOUR PYTHON FILE
1. Import streamlit
>Import streamlit as st
2. Import openai
>from openai import OpenAI
3. Import python-dotenv
>from dotenv import load_dotenv