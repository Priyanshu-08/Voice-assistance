# Multilingual Voice Assistant 


# How to run?
### STEPS:



### STEP 01- Create a python virtual environment after opening the file

```bash
# opening ur file through terminal
cd C:\Users\YourName\Documents\multimodel-virtual-AI-Assistant

```
```bash
# creating the virtual env
python -m venv env

```

```bash
# activating the env
env\Scripts\activate
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add your GOOGLE_API_KEY credentials as follows:

```ini
GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

### Finally run the following command
```bash
streamlit run app.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- Google Gemini API
- Streamlit
- Whisper
- s2t
- t2s
- gtts
- speech recognition
