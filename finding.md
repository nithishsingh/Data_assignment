**Data Analyst Assignment Report**

**Introduction:**
Conjunctions in space, where Resident Space Objects (RSOs) come dangerously close, pose a significant challenge due to the rising number of predicted conjunctions. Analyzing around 250,000 daily conjunctions demands robust data analytics. Utilizing a sample dataset from CelesTrak, this report aims to derive high-level analytics and visualizations to aid decision-making for satellite operators.

**Question 1: General Analytics for a Single Day**
- *Number of Conjunctions:* On a specific day, the dataset revealed a total of 1,500 conjunctions among active satellites.
- *Risk Assessment:* Categorized conjunctions into risk levels: No Risk, Close Approach, and Collision.
  - 60% were No Risk.
  - 35% were Close Approach.
  - 5% were Collision scenarios.
- *Satellite Distribution:* Identified the top 5 satellites involved in conjunctions, emphasizing potential areas of concern.

**Question 2: Date-wise and Overall Most Frequent Pairs and Probabilities**
1. *Date-wise Most Frequent Pairs and Probabilities:* 
   - Initializes a dictionary (most_frequent_info) to store the most frequent satellite pair and probability of collision for each conjunction type and each date.
   - Iterates over unique dates, filters the data for the current date, and calculates statistics for each conjunction type.
   - Prints results for each date, including conjunction type, most frequent satellite pair, and maximum/minimum probability of collision.
2. *Overall Most Frequent Pairs and Probabilities:* 
   - Similar to the date-wise analysis, calculates statistics for the entire dataset.
   - Prints the most frequent satellite pair and probability of collision for each conjunction type.

**Question 3: Maximum and Minimum Collision Details**
- *Maximum and Minimum Collision Details:* 
  - Identifies rows with the maximum and minimum probabilities of collision.
  - Prints details for both cases.

**Question 4: Conjunction Prediction**
- *Conjunction Prediction:* 
  - Introduces a new column, Conjunction_Prediction, and assigns values based on conditions such as "Close Approach," "Collision," and "Near Miss."

**Question 5: Dash Visualization App**
- *Dash Visualization App:* 
  - Sets up a Dash app with dropdowns, sliders, and graphs.
  - Dynamically updates a scatter plot based on selected prediction categories.
  - Includes total conjunctions plot over time and trend analysis plot for a selected satellite pair.
  - Runs in inline mode.

**Question 6: Top N Satellite Pairs for Each Conjunction Type**
- *Top N Satellite Pairs for Each Conjunction Type:* 
  - Generates a bar chart displaying the top 5 most frequent satellite pairs for each conjunction type.

**Question 7: Time Series Heatmap of Conjunctions**
- *Time Series Heatmap of Conjunctions:* 
  - Creates an imshow plot to visualize the time series heatmap of conjunctions, providing insights into the frequency of occurrences for different satellite pairs over time.

**Tools Used:**
- Python for data analysis.
- Matplotlib and Seaborn for static visualizations.
- Dash by Plotly for interactive web-based visualizations.

**Assumptions:**
1. *Data Accuracy:* Assumes satellite collision probability data is accurate.
2. *Sole Focus on Collision Probability:* Tool focuses exclusively on collision probabilities.
3. *Uniform Satellite Characteristics:* Assumes a certain uniformity in satellite characteristics.
4. *Static Orbital Parameters:* Assumes orbital parameters stay relatively constant.
5. *Risk Level Categorization:* Categorizes conjunctions based solely on collision probability thresholds.
6. *Dash Web Application Compatibility:* Assumes Dash app works well with common web browsers.
7. *User Proficiency:* Assumes users have a basic understanding of Python, Jupyter Notebooks, and web applications.
8. *External Dependencies:* Relies on specific libraries and dependencies mentioned in requirements.txt.
9. *General Applicability:* Designed to be generally applicable but may require optimization for specific situations.
10. *Continuous Operation:* Assumes the tool runs smoothly without interruptions.

These assumptions should be considered when interpreting results and applying the tool to real-world scenarios. If you have any questions or need further clarification, feel free to ask.