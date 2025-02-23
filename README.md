# LLM-Personal-trainer-streamlit

Refer to the medium article here -> https://medium.com/@mcfaddenrbenjamin/building-a-llm-personal-trainer-with-streamlit-langchain-337a8efac832

## Summary:
A streamlit application built using streamlit, langchain, and the open AI API. The application has three main features including:

* Workout plan generator: Provide some information and submit the form to generate a workout plan.

* Answer fitness questions: Select a common fitness and health related question and submit to recieve an answer.

* Workout of the day: Select a preference, and a random workout of the day will be provided to you.

The app requires you to have your own API key. The application was most recently tested using python 3.12.8. The environent can be created with the following commands in the terminal/command prompt

```BASH

python -m venv venv
cd venv/scripts
activate
pip install -r requirements.txt
```
The application can be run with the following command

```BASH
streamlit run 1_Workout_Plan_Generator.py
```

## API key management: 

There are two ways to use the app. 

* 1 - Use the public version hosted at https://llm-personal-trainer-streamlit.onrender.com/. Provide your OPEN AI API key in the sidebar, validate the key, and then use the application. 

* 2 - Clone the repository, and provide the key in the secrets.toml file which should be placed in the .streamlit folder. Your secrets.toml file should therefore contain the following
open_ai_key="OPEN_AI_KEY"


