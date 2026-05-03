 Airline Flight Price Analysis

This project explores a comprehensive dataset of flight bookings in India, focusing on the factors that influence ticket pricing, such as airline choice, flight duration, and booking lead time.

Project Structure

   `airlines_flights_data.csv`: The core dataset containing 300,153 flight records.[cite: 1, 2]
   `main.ipynb`: A Jupyter Notebook containing the Python code for data cleaning, exploratory data analysis (EDA), and visualization.[cite: 2]

 Dataset Overview

The dataset includes the following key features:
*   **Airline**: The name of the airline (e.g., SpiceJet, AirAsia, Vistara, Air India, Indigo, GO_FIRST).[cite: 2]
*   **Source & Destination**: Major Indian cities including Delhi, Mumbai, Chennai, Hyderabad, Bangalore, and Kolkata.[cite: 2]
*   **Departure & Arrival Time**: Categorized by time of day (e.g., Early Morning, Morning, Afternoon, Evening, Night).[cite: 2]
*   **Class**: Economy or Business class.[cite: 2]
*   **Duration**: Total flight time in hours.[cite: 2]
*   **Days Left**: The number of days between the booking date and the departure date.[cite: 2]
*   **Price**: The target variable (ticket cost).[cite: 2]

 Key Statistics
*   **Total Records**: 300,153[cite: 2]
*   **Average Ticket Price**: ₹20,889.66[cite: 2]
*   **Maximum Ticket Price**: ₹123,071 (Vistara Business Class)[cite: 2]
*   **Minimum Ticket Price**: ₹1,105[cite: 2]
*   **Average Duration**: 12.22 hours[cite: 2]

 Requirements

To run the analysis in `main.ipynb`, you will need the following Python libraries:
*   `pandas`
*   `numpy`
*   `matplotlib`
*   `seaborn`

 Analysis Workflow

1.  **Data Cleaning**: Removed unnecessary index columns and verified that there are **no missing values** in the dataset.[cite: 2]
2.  **Exploratory Data Analysis**: 
    *   Analyzed the frequency of flights per airline (Vistara and Air India are the most frequent).[cite: 2]
    *   Identified outliers in flight duration (max duration of 49.83 hours).[cite: 2]
3.  **Visualization**: (Contained within the notebook) investigating price trends based on booking lead time and flight class.
