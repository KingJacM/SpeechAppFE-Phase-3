# MSA-Phase-2
 
The google Speech-to-Text API requires a server side backend to run. Therefore a python FastAPI is created in order to assist.

Frontend React is just navigate to `speech` folder and run `npm install` and `npm start`
Backend Fast API:
1. `pip install fastapi'
2. `pip install google-cloud-speech'
3. `python -m uvicorn main:app --reload`

If step 3 fails, a set up of python virtual enviroment maybe needed (venv folder is also uploaded to github)
refer to https://fastapi.tiangolo.com/tutorial/ if any error regarding FastApi

google-cloud-speech only supports FLAC and some other audio types but not mp3, hence a conversion is needed. API only supports files < 60 seconds

If there's any problems on running, start an issue.