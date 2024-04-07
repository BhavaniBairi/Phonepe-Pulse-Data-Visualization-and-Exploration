# Phonepe-Pulse-Data-Visualization-and-Exploration

------------------------------------------------------------------------------------------------------
1. @Title: Phonepe Pulse Data Visualization and Exploration--README
2. @Description: A streamlit application that allows users to access and analyze data of Phonepe application used for digital payments and transactions
------------------------------------------------------------------------------------------------------


Quick Configuration Guide:
-----------------------------
To get the quick access to the different packages of python:
Create a virtual evnironment under the folder in which you are creating python(.py) file in Visual Studio Code and install below packages in cmd prompt and import them:

- import os
- import json
- import pandas as pd
- import psycopg2
- import streamlit as st
- from streamlit_option_menu import option_menu
- import plotly.express as px
- from PIL import Image
- import requests
- import matplotlib.pyplot as plt

------------------------------------------------------------------------------------------------------------------

**Data:**
----------------------------------------
Clone the data from the PhonePe Pulse Repository

--------------------------------------------------

**Creating Data Tables:**
---------------------------------------------------
The Cloned Git-hub corresponding DataFrame of given pulse data is inserted into SQL database by creating tables.

----------------------------------------------------------------

**Data Retrieval:**
--------------------------------------------------------------
Data is fetched from the SQL database into pandas Data frames and is used to dynamically update on dashboard.

--------------------------

Features:
--------------------------
Phonepe Pulse Data Visualization and Exploration provides following features:
- Analysis and the Vizualization of PhonePe Transactions on the basis of the selected Year and Quarter
- Analyse number of Registered users for the year and quarter. Also for the Brand of Phone.
- Top states, districts, postal codes who stand out for the transactions and Registrations on PhonePe
- Basic Insights on the transactions and registrations on PhonePe using Queries


