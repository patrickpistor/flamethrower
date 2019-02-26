# Server Functions

This part of the repository is responsible for the server functions that will
run the flamethrower app.

**Note: This is meant for use with Google Cloud Functions!**

## Setup

Ensure that you are using **Python 3.7**, as that is the Python interpreter
that GCP uses.

All functions must be in a file called main.py. 

## Functions

**healthz** - checks for whether the cloud endpoint is up and properly deployed.
