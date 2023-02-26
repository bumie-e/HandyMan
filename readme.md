HandyMan is a web assistant that helps you translate between any of the supported languages. 
It automatically detects the lanuage your text is written in and translates it to your required language.

Choose one of these language to get started :smiley: 

- English
- French
- Italian
- Japanese
- Russian
- Korean
- Spanish

To run this repository,

- Clone the repository
- Open your terminal and navigate to the project directory
- Do `pip install -r requirements.txt`
- Visit Azure portal
- Create a new Translator app service resource
- Visit the resource page and copy the `KEY`, `ENDPOINT`, and `LOCATION`
- Create a .env file and save the `KEY`, `ENDPOINT`, and `LOCATION` e.g 
 `KEY: <Your key here>`
 `ENDPOINT: <Your endpoint here>`
 `LOCATION: <Your location here>`

- Add the `.env` file to the project directory
- in your terminal, type `streamlit run app.py`

