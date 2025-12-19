# NYC-Motor-Vehicle-Collisions-Time-Based-Patterns

This project applies Applied Probability & Statistics concepts to a real-world crash dataset (3,000 observations) and analyzes how collisions vary by **hour**, **day of week**, and **month**. The workflow uses descriptive statistics, probability estimation (relative frequency), visualization, and a simple linear regression model.

## Key Techniques
- Descriptive statistics: counts by hour/day/month  
- Random variables: time-based outcomes  
- Expectation (sample mean)  
- Empirical probability (relative frequency)  
- Data visualization (bar charts, histogram, scatter)  
- Simple linear regression  

## Dataset
NYC Open Data — *Motor Vehicle Collisions – Crashes*.

**Tip:** This repo does not include the full dataset. Download it from NYC Open Data and place it in `data/` as:
`Motor_Vehicle_Collisions-Crashes.xlsx`

## How to Run
```bash
pip install -r requirements.txt
python src/analysis.py --data "data/Motor_Vehicle_Collisions-Crashes.xlsx"
