# Real Rstate Analytics Map

# Zillow Property Map & Price History Viewer

I created a Flask web application that visualizes real estate properties on a map and provides historical price data for individual properties. It uses **Zillow property data**, Folium for interactive maps, and BrightData API for price history snapshots. 

<img width="1766" height="863" alt="Image" src="https://github.com/user-attachments/assets/6ed5c778-30a0-49cf-b3c2-894f524c7ca0" />

<img width="1836" height="864" alt="Image" src="https://github.com/user-attachments/assets/59dd3c47-a4b1-480c-bbcb-24054d5ad7b6" />

<img width="1833" height="820" alt="Image" src="https://github.com/user-attachments/assets/f32fbcdb-aa4b-47c2-b323-647dfe58894c" />

<img width="1835" height="819" alt="Image" src="https://github.com/user-attachments/assets/0e86fc5b-5c69-47d2-bd62-45c3c77df6e8" />

---

## Features

- **Interactive Property Map**:  
  Displays properties as markers on a map, clustered for convenience. Marker colors indicate **gross rental yield**:  
  - **Green**: High yield  
  - **Orange/Yellow**: Moderate yield  
  - **Red**: Low yield  
  - **Black**: Off-market  

- **Property Details**:  
  Each marker popup shows:  
  - Address  
  - Price  
  - Bedrooms & Bathrooms  
  - Living area  
  - Gross rental yield  
  - Zestimate & Rent Zestimate  
  - Zillow link  

- **Price History**:  
  Click "Show Price History" to view a table of historic prices for that property, formatted with dates and prices.  


---
