# webappdeploy
A Simple Web Application Deployment Using Python

# Key Tasks to Create Virtual Deployment Environment
1. python3 -m venv .venv
2. source .venv/bin/activate (on mac /linux machines)
3. .venv\Scripts\activate.bat (windows CMD)
4. .venv\Scripts\Activate.ps1 (windows powershell)
5. python3 -m pip install -r requirements.txt
6. uvicorn main:app --reload  (Starts the FastAPI server after execution of python script)

The provided Python code is a basic example of a FastAPI web application:

# Key Features:

# FastAPI Framework:

    # The FastAPI framework is used to create a web application. 
    # It is known for being fast, lightweight, and easy to use for building RESTful  
      APIs.

# Endpoints (Routes):

     #Two endpoints (routes) are defined:

     - /hello: Returns a simple HTML response saying hello guys.

     - /welcome: Returns a more formatted HTML response saying <b>welcome guys. This is your portal</b> (in bold text).

# HTML Response:

   #The use of HTMLResponse ensures that the returned content is interpreted as HTML by the browser, allowing for structured and styled text.


# Purpose

  #This code provides a simple example of how to create HTML-based responses using FastAPI. It's often useful for:

    #Serving HTML content dynamically.

    #Testing FastAPI endpoints with simple responses.

    #Building lightweight web APIs or hybrid web services.

