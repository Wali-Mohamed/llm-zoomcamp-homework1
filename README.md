Simply create a file name ".env" and write your API key in Like this : "API_KEY = YOUR_API_KEY"

then run "pip3 install python-dotenv" in your cmd

then in your code, add some lines :

from dotenv import load_dotenv
import os

load_dotenv()

API_KEY=os.getenv("API_KEY")
