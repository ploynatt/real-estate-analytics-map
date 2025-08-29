# Real Rstate Analytics Map

# Zillow Property Map & Price History Viewer

I created a **Flask web application** that visualizes real estate properties on a map and provides historical price data for individual properties. It uses **Zillow property data**, Folium for interactive maps, and BrightData API for price history snapshots. 

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
