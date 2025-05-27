 Energy Bill Forecast

This project is a streamlined data science application designed to forecast monthly electricity bills using time series analysis and user input. By combining Python, Prophet, and interactive interfaces, it allows users to estimate future energy costs based on historical consumption trends.

# What It Does;
*Loads historical energy price data (from CSV).
*Uses Prophet to forecast future electricity unit prices.
*Allows users to input custom year and consumption (kWh).
*Instantly calculates expected monthly bill.
*Visualizes historical trends and future projections.

# Technologies Used;
*Python 3.10+
*Prophet: For time series forecasting.
*Pandas: Data manipulation.
*Streamlit (optional UI): For creating a simple web interface.

#Why This Project Matters
*Energy cost forecasting is a critical tool for:
*Households managing expenses.
*Utility companies building consumer tools.
*Governments and researchers modeling consumption behavior.

This notebook demonstrates how a single data scientist can build a scalable, interpretable forecast pipeline with minimal code and maximum insight.

#How to Run;
*Clone the repo.
*Install requirements:
pip install pandas prophet

*Run the notebook:
jupyter notebook energy-bill-forecast.ipynb

*(Optional) Run the Streamlit version:
streamlit run app.py

# Example Output;
*Forecast plot with confidence intervals.
*Calculated monthly cost based on user kWh input.

#Potential Improvements;
*Integrate with real-time tariff APIs.
*Add seasonal effects and holidays.
*Deploy as a web dashboard for utility customers.

#Ideal For;
*Data science portfolios
*ML/AI engineer project showcases
*Internship applications in energy, utilities, or tech

Made with ⚡ by [Fatih Çetinkaya]

