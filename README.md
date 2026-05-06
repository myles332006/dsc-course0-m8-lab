# Aviation Accident Analysis

This project analyzes aviation accident data to evaluate aircraft safety with a focus on:

-Fatal and serious injury rates
-Aircraft destruction rates
-Differences across aircraft types (small vs large)
-Impact of operational and environmental factors

The goal is to provide data-driven recommendations to an airline/insurance client on safer aircraft makes and models.

# EXPLORATORY DATA ANALYSIS
1) Aircraft Makes Analysis
Identified top manufacturers with:
   - Lowest injury rates
   - Lowest destruction rates
   - Compared small vs large aircraft

2. Plane-Type Analysis (Make + Model)
Evaluated safety at a more granular level
Highlighted:
 -Safest aircraft models
 -Variability in outcomes

3. Distribution Analysis
Used:
  -Violin plots (small aircraft)
  -Strip plots (large aircraft)

Showed:
Consistency vs variability in safety

# Key Factors Investigated
1) Weather Conditions
Poor weather (IMC) → higher injury and destruction rates
Clear weather (VMC) → lower severity


2) Phase of Flight
Highest risk:
  -Takeoff
  -Landing
  -Approach

Lowest risk:
  -Cruise
  -Taxi

# Key Findings
1) Large aircraft are significantly safer
 -Lower injury fractions
 -More consistent outcomes

2) Small aircraft show higher variability
   -More sensitive to external factors

3) Certain makes/models consistently outperform others
  -Low average injury + low variability

4) Operational factors matter
  -Weather and flight phase strongly influence accident severity





🏆 Recommendations
✅ Preferred Aircraft


Large passenger aircraft with:


Low injury rates


Low destruction rates


High consistency




⚠️ Caution


Small aircraft with:


High variability in outcomes


Higher sensitivity to weather and pilot conditions




📌 Risk Mitigation


Improve:


Weather-based decision-making


Pilot training for critical flight phases


Operational safety protocols





🛠️ Tools & Technologies


Python


Pandas (data manipulation)


Matplotlib / Seaborn (visualization)


Jupyter Notebook



📁 Project Structure
├── data/│   └── AviationData.csv├── notebooks/│   └── analysis.ipynb├── outputs/│   ├── cleaned_data.csv│   ├── charts/│   └── tables/├── README.md

🚀 How to Run


Install dependencies:


pip install pandas matplotlib seaborn


Run the notebook:


jupyter notebook


Open:


analysis.ipynb

📌 Conclusion
This analysis demonstrates that aircraft type, manufacturer, and operational conditions all play critical roles in aviation safety. By focusing on low-risk aircraft models and mitigating environmental risks, stakeholders can significantly reduce both human and financial losses.

👤 Author
Your Name

If you want, I can:


Turn this into a GitHub-ready version with badges


Add visual examples inside README


Or tailor it for submission grading criteria

