# MistralAPI-streamlit
A streamlit ChatBot running Mistral-Small-24B with free API calls

<img src='https://github.com/fabiomatricardi/MistralAPI-streamlit/raw/main/mistralai.png' width=950>


## Instructions

- Clone the repo
- create the virtual environment
```bash
python -m venv venv
```
- activate the virtual environment
```bash
.\venv\Scripts\activate
```
- Install the dependencies
```bash
pip install streamlit mistralai 
```
- from the terminal with the venv activated, run
```bash
streamlit run .\st-Mistral-API.py
```

---


### The running app
- you need to add your own API key (alert message if missing)
- you can choose among 3 models
- you can clear the chat (alert message)
- in the terminal you can see what model is called
<img src='https://github.com/fabiomatricardi/MistralAPI-streamlit/raw/main/st-MistralApp-runLG.gif' width=1100>
