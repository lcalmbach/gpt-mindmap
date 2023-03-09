# gpt-mindmap
This app uses the openai-api to create a mindmap based on a user specified theme. The codes originates from Jacob Ferus  in https://medium.com/gitconnected/ai-generated-mind-maps-with-the-chatgpt-api-in-python-and-streamlit-bad9cd63f402

Prerequisites: 
you need a API code from openai. If you dont have one, see the article above on how to get one. Then set the environment variable:
```
> set OPENAI_API_KEY = "YOUR_SECRET_KEY"
```
Also change the variable3 LOCAL_HOST in the app.py file on line 22 to your machine name:

To build your app locally on a windows machine:

```
> https://github.com/lcalmbach/gpt-mindmap.git
> cd gpt-mindmap.git
> py -m -venv .venv
> pip install -r requirements.txt
> .venv\scripts\activate
```
