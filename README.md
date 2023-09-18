# LLM-Personal-trainer-streamlit
LLM powered personal trainer built for the streamlit LLM hackathon, September 2023.

Summary:
A streamlit application built using streamlit, langchain, and the open AI API. The application has three main features including:

* Workout plan generator: Provide some information and submit the form to generate a workout plan.

* Answer fitness questions: Select a common fitness and health related question and submit to recieve an answer.

* Workout of the day: Select a preference, and a random workout of the day will be provided to you.

The app requires you to have your own API key.

python 3.11.5
python -m venv venv
cd venv/scripts
activate

pip install -r requirements.txt

streamlit run 1_Workout_Plan_Generator.py


API key management: 

There are two ways to use the app. 

* 1 - Use the public version hosted on streamlit cloud. Provide your OPEN AI API key in the sidebar, validate the key, and then use the application. 

* 2 - Clone the repository, and provide the key in the secrets.toml file which should be placed in the .streamlit folder. 


