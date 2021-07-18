# Project's Title
   ### Country Capital API
# Project's Description
   **API written in Python and Flask that returns the name of the country if a capital city is provided.**
   **The ASGI server Uvicorn is used to serve this API. Also, there is a microservice endpoint for this API available at**
   >https://example.com/country-capital/[query-params]

   **that can be used by any project in the organization to consume this API.**

# Technologies used
* **[Python3](https://www.python.org/downloads/)**       - Python is an interpreted high-level general-purpose programming language.
* **[Virtualenv](https://virtualenv.pypa.io/en/stable/)**- A tool to create isolated virtual environments for python.
* **[Flask](https://flask.palletsprojects.com/en/2.0.x/)**                          - Flask is a micro web framework written in Python.
* **[ASGI server](https://www.uvicorn.org/)**-Uvicorn is a lightning-fast ASGI server implementation, using uvloop and httptools.
* Dependencies can be found in the requirements.txt file on the root folder.

# Setup local dev environment
## 1. Creating Virtual Environments.
      python3 -m venv python-env
## 2. Need to activate virtual environment.
     On Windows, run: python-env\Scripts\activate.bat
     On Unix or MacOS, run:source python-env/bin/activate
## 3. Installing dependencies from requirement file.
      python3 -m pip install -r requirements.txt
## 4. Run Server
      uvicorn country_api:app --reload --port 5000
## 5. Visit in browser
      http://localhost:5000
      

