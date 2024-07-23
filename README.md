# -01--Improvise-Python-App-using-GitHub-Copilot-available-
 01- Improvise Python App using GitHub Copilot available 
# main.py

from fastapi import FastAPI
from pydantic import BaseModel

app = FastAPI()

# Add a Pydantic model for the input JSON
# Create a Pydantic model with a single field called "text"
class TextRequest(BaseModel):
    text: str
   
