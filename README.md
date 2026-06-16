# NYC-COLLISIONS-ANALYSIS-DASHBOARD

Analyzed 238K NYC traffic collisions using Power BI to identify accident hotspots, peak collision periods, dangerous roadways, and key contributing factors. Delivered actionable insights to support road safety planning and accident reduction initiatives.


![](https://github.com/Amarh16/NYC-COLLISIONS-ANALYSIS-DASHBOARD/blob/main/IMG_1667.jpg)


## Executive Summary

This analysis examines traffic collision patterns across New York City using collision data containing approximately 238,000 recorded accidents. The objective was to identify when accidents occur most frequently, where they are concentrated, and the primary factors contributing to both overall and fatal collisions.

The findings reveal clear temporal patterns, with accident volumes peaking during specific months, weekdays, and rush-hour periods. Certain streets consistently record significantly higher collision counts, while driver behavior factors such as distraction, unsafe speed, and failure to yield are among the leading contributors to accidents and fatalities.

The analysis provides actionable insights that can support traffic management authorities, urban planners, and public safety agencies in improving road safety and reducing accident rates.

## Methodology Note:

The findings presented in this analysis are based on reported collision records contained within the NYC Traffic Collisions dataset. The dashboard focuses on identifying patterns, trends, and relationships within the available data rather than establishing direct causation. Factors such as reporting inconsistencies, missing contributing-factor information, and external conditions not captured within the dataset may influence the results. Therefore, the insights should be interpreted as indicators of potential risk areas and accident patterns that support data-driven decision-making rather than definitive explanations of collision causes.




## 1. Key Performance Indicator (KPI)

| KPI | Value |
|-----|-------|
| Total Accidents | 238,000 |

## Key Metrics:

Question 1.
Compare the number of total accidents by month. Do you notice any seasonal patterns?

Question 2.
Break down accident frequency by day of week and hour of day. Based on this data, when do accidents
occur most frequently?

Question 3.
On which particular street were the most accidents reported? What does that represent as a number of all
reported accidents?

Question 4.
What was the most common contributing factor for the accidents reported in this sample? What about fatal accidents specifically?

## Skills/Concepts Demonstrated:

- Power BI
- DAX
- Data Modelling
- Data Visualisation


![](https://github.com/Amarh16/NYC-COLLISIONS-ANALYSIS-DASHBOARD/blob/main/IMG_1624.jpg)

### Interpretation
The dataset contains approximately 238,000 recorded collisions, indicating a substantial volume of traffic incidents across New York City. This high number highlights the importance of understanding accident patterns and identifying risk factors that contribute to collisions throughout the city.

## 2. Accident Trends by Month

### Findings
Monthly accident volumes show noticeable variation throughout the year.
Key observations include:

- March recorded the highest accident volume at approximately 25,000 accidents
- January recorded approximately 23,000 accidents
- February recorded approximately 21,000 accidents
- Most remaining months recorded between 17,000 and 20,000 accidents

### Insight
The increase in accidents during March may be influenced by:

- Increased traffic activity
- Seasonal weather transitions
- Higher travel volumes

The relatively stable accident levels across most months suggest that traffic safety challenges remain consistent throughout the year rather than being limited to specific seasons.

### Business Impact
Understanding seasonal accident trends enables transportation authorities to:

- Allocate enforcement resources more effectively
- Increase public safety campaigns during high-risk periods
- Improve traffic monitoring during peak months

## 3. Accident Trends by Hour

### Findings
The hourly analysis reveals distinct traffic accident patterns throughout the day.
Major peaks occur during:

#### Morning Rush Hour
Approximately:
7 AM to 9 AM

#### Evening Rush Hour
Approximately:
3 PM to 6 PM

The highest accident counts occur around:
4 PM to 5 PM
Approximately 15,000 accidents

The lowest accident levels occur during early morning hours:
2 AM to 5 AM

### Insight
The strong relationship between accident frequency and commuting periods suggests that traffic density plays a major role in collision occurrence.

Factors likely contributing include:

- Heavy traffic congestion
- Driver fatigue
- Increased distractions
- Aggressive driving behaviors during peak travel periods

### Business Impact
Traffic management agencies should prioritize:
- Rush-hour traffic control measures
- Congestion reduction strategies
- Targeted road safety campaigns during peak periods

## 4. Accident Trends by Day of Week

### Findings

Accident volumes are highest on weekdays.

Top days include:

| Day | Approximate Accidents |
|-----|-------|
| Wednesday | 34.0K |
| Thursday | 37.4K |
| Friday | 34.6K |
| Saturday | 34.0K |
| Sunday | 31.2K |

### Insight
The data indicates that accident activity increases significantly toward the end of the workweek.
Possible reasons include:

- Higher traffic volumes
- Increased business activity
- Weekend travel preparation
- Driver fatigue accumulated during the week

### Business Impact
Law enforcement agencies may consider increasing:

- Traffic patrols
- Road safety monitoring
- Driver awareness campaigns
  
during higher-risk weekday periods.

## 5. Top Streets by Accident Count

### Findings

The streets with the highest recorded accident volumes include:

| Street | Approximate Accidents |
|-----|-------|
| Belt Parkway | 3.7K |
| Broadway | 2.8K |
| Atlantic Avenue | 2.2K |
| Long Island Expressway | 2.2K |
| Brooklyn Queens Expressway | 2.2K |

Other high-risk roads include:

- FDR Drive
- 3rd Avenue
- Grand Central Parkway
- Cross Island Parkway
- Major Deegan Expressway

### Insight
These roads are among New York City’s busiest transportation corridors and experience significant traffic volumes daily.
High accident rates may result from:

- Traffic congestion
- Complex intersections
- Lane merging activity
- High-speed travel conditions

### Business Impact
These locations should be prioritized for:

- Traffic safety audits
- Road infrastructure improvements
- Enhanced signage
- Speed enforcement initiatives

## 6. Leading Causes of Accidents

### Findings
The Treemap analysis identifies the most common contributing factors:

#### Top Factors
- Driver Inattention / Distraction
- Unspecified Causes
- Failure to Yield Right of Way
- Following Too Closely
- Passing or Lane Changing Violations
- Unsafe Speed

### Insight
Human behavior is the dominant contributor to traffic accidents.
The prominence of driver distraction suggests increasing risks associated with:

- Mobile phone use
- In-vehicle distractions
- Reduced driver attention

### Business Impact
Traffic safety programs should focus on:

- Distracted driving prevention
- Driver education campaigns
- Enhanced enforcement measures

## 7. Fatal Accident Analysis

### Findings
Among collisions involving fatalities, the most common contributing factors include:

| KPI | Value |
|-----|-------|
| Unspecified | 174 |
| Unsafe Speed | 130 |
| Driver Inattention/Distraction | 73 |
| Failure to Yield Right of Way | 46 |
| Traffic Control Disregarded | 33 |
| Pedestrian/Bicyclist Related Factors | 27 |
| Alcohol Involvement | 25 |

### Insight
Fatal accidents are strongly associated with:

- Excessive speed
- Driver distraction
- Traffic violations

Unsafe speed emerges as the most significant identifiable cause of fatal collisions.

### Business Impact
Reducing fatalities may require:

- Stricter speed enforcement
- Improved traffic control compliance
- Enhanced driver education programs
- Increased public awareness initiatives

## Overall Conclusions

The analysis identifies four major themes:

### 1. Traffic Volume Drives Risk
Accident frequency increases significantly during:

- Peak commuting hours
- Busy weekdays
- High-traffic road corridors

### 2. Human Error Remains the Primary Cause

Driver behavior factors account for the majority of accidents.
Key contributors include:

- Driver distraction
- Unsafe speed
- Failure to yield

### 3. Certain Roads Present Higher Risk

A relatively small number of streets account for a disproportionately large share of collisions.

### 4. Fatal Accidents Are Closely Linked to Speed and Distraction

The data shows that unsafe driving behaviors greatly increase the likelihood of severe outcomes.

## Recommendations

### Recommendation 1: Strengthen Distracted Driving Enforcement
Priority: High

Actions:

- Increase mobile phone enforcement operations
- Expand public awareness campaigns
- Install anti-distraction signage

Expected Outcome:

- Reduction in distraction-related accidents
- Improved driver attentiveness

### Recommendation 2: Target High-Risk Roads
Priority: High

Actions:

- Conduct road safety audits
- Improve signage and lane markings
- Review intersection design

Expected Outcome:

- Reduced collision frequency on major corridors

### Recommendation 3: Enhance Speed Management Programs
Priority: High

Actions:

- Increase speed camera coverage
- Strengthen speed enforcement
- Review speed limits on high-risk roads

Expected Outcome:

- Lower fatal accident rates
- Improved overall road safety

### Recommendation 4: Focus Resources During Peak Risk Periods
Priority: Medium

Actions:

- Increase patrol presence during rush hours
- Improve traffic signal management
- Deploy congestion mitigation strategies

Expected Outcome:

- Reduced accident frequency during peak travel periods

## Final Business Recommendation
New York City traffic authorities should prioritize initiatives aimed at reducing driver distraction, controlling excessive speed, and improving safety on high-risk roads. The analysis demonstrates that collisions are largely driven by traffic density and human behavior, making targeted enforcement, infrastructure improvements, and public awareness campaigns the most effective strategies for reducing accidents and fatalities across the city.




