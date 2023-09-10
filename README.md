INTEL UNNATI – ROAD SAFETY ANALYSIS  

Abstract:   

Our team analyzed real-world data to focus on understanding patterns and issues related to road safety. Our main objective was to develop methods that can predict road safety incidents and offer solutions based on the knowledge we gained. These solutions can be implemented in real-life situations to improve road safety. Additionally, we enhanced our analysis by incorporating data, such, as accident areas (known as blackspots) information about hospitals and schools, and details about the road network. Our analysis covered aspects, including studying collision patterns analysing time and location factors understanding vehicle behavior examining event timestamps conducting analysis, and identifying blackspots. We also made efforts to suggest ways to enhance road safety. Throughout this project, we leveraged machine learning techniques to extract insights, from the data. Furthermore, we used Power BI Tools to visualize the results of our analysis in a way that's easy for stakeholders and decision-makers to understand. 

 

Introduction 

This report dives into a substantial dataset comprising 21,326 rows and 7 essential 'Alert' columns. These alerts stem from ADAS in various vehicles, providing critical insights into road safety events. The dataset covers diverse event types, like Forward Collision Warnings, Pedestrian Collision Warning, Lane Departure Warning, and Headway Monitoring and Warning. Additionally, it includes key details such as event Date and Time, precise Geographical coordinates (Lat, Long), Vehicle identification, and recorded Speed. Our report aims to uncover hidden patterns, identify emerging trends, and derive actionable insights. These findings have the potential to enhance road safety and inform decision-making in the realm of advanced driver assistance systems and road safety management. 

Predictive Analysis  

In this analysis, we utilized a range of Python packages to handle data visualize information perform calculations, and use logistic regression for predictive modelling. Our main aim was to predict the probability of vehicles being involved in collisions based on their speed. By applying regression, a technique suitable, for binary classification tasks we used a likelihood function to estimate the probabilities of collisions. Our analysis comprised steps; initially, we divided the dataset into two groups. "Likely collision vehicles" and "non-collision vehicles”. Based on our models’ predictions. Then we employed data visualization techniques to differentiate between these two categories. Furthermore, we created a visualization to explore how vehicle speed is related to the probability of collision within the " collision vehicle" group and also non-collision vehicles. These findings provide insights into understanding. Potentially reducing collision risks associated with vehicle speed making them highly relevant, for making informed decisions in this context. 

Time and Location Analysis 

 The accident data has revealed significant insights into accident patterns and their alignment with identified black spots. Among these findings, one prominent location stands out with the highest number of accidents, situated at the geographical coordinates (Lat, Long): (12.992198, 80.182455), which happens to be close to Chennai International Airport. This discovery highlights a critical area in need of heightened safety measures and attention. It has delved into the temporal aspect of accidents, revealing intriguing trends in collision alerts generated by advanced driver assistance systems (ADAS) in vehicles. It was observed that Fridays witness the highest incidence of collision alerts, closely followed by Thursdays, Tuesdays, and Wednesdays, while Sundays record the least. This temporal pattern can be attributed to the presence of colleges, working offices, and schools during weekdays, causing increased traffic and potential accident risks. In contrast, weekends, particularly Sundays, exhibit a lower frequency of collision alerts due to reduced vehicular activity. These findings shed light on the importance of targeted safety measures and traffic management strategies during weekdays to mitigate the risk of accidents in these areas. 

Event Timestamp Analysis 

The analysis reveals a notable pattern in collision speeds, with the majority falling within the range of 55 to 60 mph. This range is particularly significant, as it represents a substantial frequency of collisions, occurring approximately 4,000 times. Further exploration of the time of day when collisions tend to happen highlights interesting findings. Collisions are notably concentrated during two specific periods: in the early mornings around 7 o'clock and during the evening at 5 o'clock. However, it's striking to note that the highest frequency of alert messages, totalling 5,000 occurrences, corresponds to the evening hour at 5 o'clock. This temporal concentration could be attributed to the evening rush hour when commuters, including individuals returning home from colleges, schools, and offices, are on the road. The heightened alert frequency during this time may signify increased traffic and potentially risky driving behaviors. These insights not only shed light on the distribution of collision speeds but also provide a valuable understanding of the time patterns surrounding collision alerts. Such information can be instrumental in developing targeted safety measures and interventions, particularly during these critical hours, to enhance road safety and mitigate collision risks. 

Blackspot Identification           

Our analysis reveals significant insights into the distribution of alert messages within Chennai city limits. Notably, the highest concentration of alert messages occurs along certain key roadways. Airport Road stands out with the highest alert count, totalling 16 instances. This heightened alert frequency on Airport Road can be attributed to a prevalent practice of car owners parking their vehicles on the highway to avoid parking charges at the airport. This observation draws from historical data and suggests a compelling reason for this pattern. Anna Salai Mount Road closely follows in terms of alert frequency. This road is home to numerous corporate head offices and intersects with several other major roads, leading to heavy traffic and a higher likelihood of incidents prompting alerts. Tambaram Bus Stand also features prominently in the alert count, likely due to its proximity to a busy railway station and consistent highway traffic. Pycrofts Garden Road, near Crescent School, sees increased alerts, possibly due to its proximity to highways and educational institutions. Additionally, Crescent College's location near schools, tourist attractions like the zoological park, and its accessibility contribute to heightened traffic and alert occurrences. These findings provide valuable insights into the spatial distribution of alert messages and can inform targeted safety measures and traffic management strategies in these specific areas to enhance overall road safety within Chennai city limits. 

Geospatial analysis  

In our report, we emphasize the importance of accessibility to healthcare facilities by providing a list of hospitals in key areas within Chennai. For individuals near Mount Road, hospitals such as Kauvery Hospital Chennai, Life Care Hospital, and Bharathirajaa Hospital and Research Centre offer essential medical services. In the vicinity of the airport, options include SESHAS DENTAL SPECIALITIES and CM Hospital. For those near Pycrofts Garden Road, Pavithra Hospitals Pvt Ltd and Apollo Hospital Chennai are available to cater to healthcare needs. Additionally, the area around Tambaram Bus Stand benefits from the presence of Hindu Mission Hospital. Ensuring access to healthcare facilities in these strategic locations is vital for addressing medical emergencies and promoting the well-being of residents and visitors in Chennai. 

Solution Recommendations 

One potential solution to enhance road safety involves utilizing ADAS systems to issue cautions for reduced speed, promote awareness, and encourage the use of seat belts when vehicles enter blackspot regions. By examining driver behavior patterns, we have the opportunity to offer discounts on insurance and vehicle services based on their speed and vehicle usage habits. This approach can serve as an incentive for safer driving practices, ultimately contributing to accident prevention. Establishing an automated emergency service within the ADAS system, enabling it to promptly contact emergency services, including the police, ambulance services, and the accident victim's family members, in the event of an accident. Automated puncture detection with the option to recommend the nearest service center or request roadside assistance. Establishing a vehicle maintenance system to proactively prevent mechanical failures. This includes implementing speed limit monitoring, monitoring vehicle alignment, detecting brake pad damage, and assessing suspension. Enhancing road infrastructure in the hotspot area by implementing traffic policies, installing traffic signage, and improving road construction. 

Conclusion 

Our analysis, primarily driven by machine learning and visualized through Power BI, has unveiled critical insights into Chennai's road safety and accident patterns. Our predictive analysis, fuelled by Python packages, focused on collision likelihood based on vehicle speed. Notably, we discovered a common practice of parking on Airport Road to evade airport fees, contributing to a high alert count. Increased alerts were observed on Anna Salai Mount Road, Tambaram Bus Stand, Pycrofts Garden Road, and areas around Crescent College, each with its unique contributing factors. To enhance road safety, our findings recommend implementing ADAS systems for safer driving, automated emergency services, incentives for responsible driving, and road infrastructure improvements in hotspot zones. For detailed code and outputs, please refer to our GitHub link, ensuring informed decisions and action plans on Road safety. 

 

 
