# streamlit_user_device

Get user device as desktop | tablet | mobile

## Installation:
pip install streamlit-user-device

## Example:

import streamlit as st  
from streamlit_user_device import user_device

device = user_device()

if device:  
    st.write(device)
    
