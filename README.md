# Python-Project-on-NEO_Distance_and_Frequency_Tracker  
I used core concepts from the DATA SCIENCE TOOLBOX: PYTHON PROGRAMMING to analyze Near-Earth Object (NEO) data from NASA.

🌠 Data Loading & Inspection  
📥 Loaded the NEO dataset (CSV) using pandas.  
🧾 Checked dataset info: data types, non-null counts, and structure.  
📊 Explored with .describe(), .head(), and .tail().  
📌 Examined unique object names, orbiting bodies, and approach dates.

🧹 Data Cleaning & Transformation  
🧼 Removed or filled missing values as needed.  
🏷️ Renamed columns for clarity (e.g., 'relative_velocity.kilometers_per_hour' → 'Velocity_kmph').  
🔍 Filtered only Earth-approaching asteroids.  
📅 Converted 'close_approach_date' to datetime format.

📈 Trend Analysis & Visualization  
📆 Grouped data by year to analyze approach frequency over time.  
📊 Created bar plots for yearly NEO approaches.  
🚀 Analyzed object sizes, velocities, and distances across years.  
📉 Plotted line graphs showing average velocity and closest approach distances.  

📊 Correlation Analysis  
🧊 Computed correlation between size, velocity, and distance.  
🔥 Visualized correlations using Seaborn heatmaps.

🛰️ Category-Based Analysis  
🌐 Compared close approaches by orbiting body and observation method.  
📏 Compared NEOs based on size categories (small, medium, large).  
🛸 Analyzed frequency of flybys within different distance thresholds.

🧠 Tools & Libraries  
🔧 Pandas, NumPy, Matplotlib, Seaborn  
📅 Skills Applied: EDA, Data Cleaning, Time Series Analysis, Visualization, Correlation Analysis

📌 This project helped build intuition on data-driven storytelling and interpreting real-world space data through Python.
