### Uber Pickups in NYC – Streamlit App
This is a simple Streamlit web application that visualizes Uber pickups in New York City. The app allows users to explore the number of pickups by hour and visualize them on a map interactively. It uses publicly available Uber data from September 2014.
Features
Load and display Uber pickup data (10,000 rows by default).
Filter rides by hour using an interactive slider.
Map visualization of pickups by hour using Streamlit's st.map.
Optional raw data display with a checkbox.

### Requirements
Python >= 3.7
Streamlit
Pandas
NumPy

### Install the required libraries using pip:
pip install streamlit pandas numpy

### Run the Streamlit application:
streamlit run app.py
The app will open in your browser at http://localhost:8501.
Use the slider to select the hour you want to visualize. The map will automatically update to show pickups at the selected time.
If you want to view the raw dataset, check the Show raw data checkbox.

### Notes
Designed for educational purposes and demonstration of Streamlit live data visualization.
Works best with a small subset of data (10,000 rows) for performance reasons. Increase rows cautiously for larger datasets.
