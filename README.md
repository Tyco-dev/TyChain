**Activate virtual environment**

Mac:
`source venv/bin/activate`

Windows:
`venv\Scripts\activate`


**Install all packages**

`pip install -r requirements.txt` (pip3 if on mac)


**Run the tests**

Make sure user activates the virtual environment. 

`python -m pytest backend/tests` (python3 if on mac)

**Run the application and API**

Make sure user activates the virtual environment.

`python -m backend.app`

**Run a peer instance**

Make sure user activates the virtual environment. 

`export PEER=True && python -m backend.app`


**Run the front end**

In the frontend directory run:
`npm run start`


**Seed the backend with data**

Make sure user activates the virtual environment. 

`export SEED_DATA=True && python -m backend.app`