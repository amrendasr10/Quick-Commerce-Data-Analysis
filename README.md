**Quick commerce** is a fast-paced industry focused on **rapid delivery**, featuring platforms like **Swiggy Instamart and Zepto**,,. This project utilizes **Python** to conduct a comprehensive **data analytics study** on a synthetic dataset containing **1 million records**,. It addresses critical business questions regarding **revenue, customer ratings, and operational efficiency**,,,. By examining the correlation between **delivery speed and satisfaction**, the project links analytical techniques to real-world **Q-Commerce performance**,. The final **mini dashboard** provides a visual summary of KPIs, demonstrating how data science uncovers insights for this high-speed industry,,.
This detailed report is structured for a professional presentation based on the Python-based Quick Commerce (Q-Commerce) data analytics project.

### **1. Data Preprocessing & Cleaning**
A significant portion of the project focused on transforming raw data into a reliable format:
*   **Handling Missing Values:** 
    *   Rows with missing **City** data (approx. 52,000) were dropped.
    *   **Item Counts** were filled using the **mode** (19 items),.
    *   **Ratings** were imputed using **group-wise means** based on company and delivery time to maintain accuracy,,.
*   **Outlier Management:** Order values were filtered to remove extreme outliers (values > 2,500) to prevent skewed analysis,.
*   **Type Casting:** Order IDs were converted to strings, and various float columns were rounded and cast to integers for cleaner processing,,.

---

### **2. Business Performance Insights**
The presentation should highlight these key performance metrics:
*   **Revenue Leadership:** **Swiggy Instamart** achieved the highest total revenue, while **Geomart** recorded the lowest,.
*   **Average Order Value (AOV):** Swiggy Instamart led with an AOV of **644**, whereas Geomart trailed at **482**,.
*   **Customer Satisfaction:** **Blinkit** maintained the highest average customer rating (above 3.5), significantly outperforming **Dunzo** (2.4),.
*   **The Discount Paradox:** Analysis revealed that while discounts increase the average order value (from 476 to 712), they simultaneously decrease the number of items per order,,.

---

### **3. Operational Efficiency Analysis**
A critical part of the project involved calculating an **Efficiency Score** using **MinMaxScaler** to normalize total orders and delivery times,,.
*   **Top Performer:** **Zepto** was identified as having the best operational efficiency (high order volume with low delivery times),.
*   **Expansion Strategy:** Based on a composite of ratings, delivery speed, and order volume, the study recommends **Blinkit** and **Zepto** expand into cities like **Bangalore, Chennai, and Pune**,.

---

### **4. Interactive Visualizations & Dashboard**
The project concluded with advanced visual tools for stakeholders:
*   **Bubble Chart:** A Plotly-based interactive chart visualized the relationship between order volume (x-axis), delivery speed (y-axis), and efficiency score (bubble size),,.
*   **KPI Dashboard:** A mini-dashboard was developed featuring four high-level cards:
    1.  **Total Order Volume**,.
    2.  **Total Revenue**,.
    3.  **Average Delivery Time** (16.51 minutes),.
    4.  **Average Customer Rating** (3.04),.
