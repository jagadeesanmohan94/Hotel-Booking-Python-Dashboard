# Hotel-Booking-Python-Dashboard

Hotel Booking using python Dashboard

Dashboard link: 

Hotel_Booking_Analysis.ipynb.

![Image](https://github.com/user-attachments/assets/6b81728b-34c7-4187-a063-fe3e418e57f8)


⭐  Description 


“Performed an end-to-end exploratory data analysis (EDA) on hotel booking patterns using Python, Pandas, and Seaborn. Analyzed market segment contributions, guest arrival distributions, room type preferences, and global geographic demand. Built data visualizations including pie charts, histograms, KDE plots, time-series graphs, and geographic heat maps. Extracted actionable insights to assist pricing strategy, marketing focus, seasonality planning, and customer segmentation.”

![Image](https://github.com/user-attachments/assets/9caadb9f-9e38-4ca1-a780-2dc2533340c4)


📌 1. Market Segment Distribution – Pie Chart
Objective:
To understand the distribution of guest bookings across different market segments.
Insights:

Online Travel Agencies (Online TA) contribute the largest portion of bookings, accounting for ~59% of total reservations.
➤ This shows heavy dependency on digital channels for customer acquisition.
Offline TA/TO (Travel Agents/Tour Operators) represent ~15.9%, indicating a strong traditional travel partner network.
Direct bookings (13.5%) show potential for increasing revenue by improving direct marketing and loyalty strategies.
Corporate (4.9%), Groups (5.6%), and Complementary bookings form smaller but important revenue streams.
Aviation and Undefined segments represent minimal volume and can be deprioritized in marketing focus.

Value Added:
This analysis helps identify high-performing channels and supports decision-making around promotions, pricing strategy, and digital marketing investments.

![Image](https://github.com/user-attachments/assets/6744d4eb-3763-4bc8-99f3-cedfbb51976c)

📌 2. Guest Arrival Distribution – Histogram + KDE Plot
Objective:
To study the distribution pattern of guest arrivals and identify seasonality or clustering.
Insights:

The histogram and KDE curve show a bell-shaped (near-normal) distribution.
Most guest arrivals cluster between 120 – 200 arrivals per day, with peak density around ~160–180 guests.
Very low frequency days (<50 guests) and high-frequency spikes (>250 guests) exist but are rare.

Value Added:
A near-normal distribution indicates predictable arrival patterns, helping with:

Staffing
Inventory planning
Revenue forecasting
Dynamic pricing models

![Image](https://github.com/user-attachments/assets/12a4c06c-4045-4ccf-be85-0f576bf5ea93)

📌 3. Normal Distribution Diagram (Bell Curve Reference)
This visual demonstrates the empirical rule (68–95–99 rule), providing a conceptual foundation for interpreting the KDE curve.
It reinforces how guest arrivals follow a predictable statistical behavior, enabling the use of:

Confidence intervals
Forecasting models
Anomaly detection techniques

![Image](https://github.com/user-attachments/assets/34c0b208-ad8c-4912-b4a4-50b054d04d6c)

📌 4. Geographic Heat Map – Home Country of Guests
Objective:
To identify the geographic origin of hotel guests globally.
Insights:

The highest volume of guests is from European countries, especially those shaded in bright yellow (~15k guests).
Significant contributions also come from the USA, Brazil, and several Asian regions.
These geographic insights highlight where marketing campaigns and partnerships would be most effective.

Value Added:
This supports:

Regional pricing
Country-specific promotions
Targeted ads on OTA platforms
Language/culture-specific services

![Image](https://github.com/user-attachments/assets/40a90276-051a-41fb-82de-3c4137b759c5)

📌 5. Market Segment vs Room Type – Bar Graph
Objective:
To analyze which room types are most frequently reserved by different market segments.
Insights:

Online TA and Offline TA/TO segments have the highest room-type diversity, dominating types A, D, E, G.
    Corporate guests prefer consistent mid-range room types.
Complementary bookings show very low volume but mostly choose lower-tier rooms.
Aviation segment strongly focuses on a single room type, indicating fixed corporate contracts.

Value Added:
This analysis helps optimize:

Inventory management
Room-type pricing
Segment-based upselling strategies

![Image](https://github.com/user-attachments/assets/106e5088-9c92-42da-808b-5f61ef0b2263)

📌 6. Time Series Plot – Daily Guest Arrivals
Objective:
To analyze seasonality and trends over 2015–2017.
Insights:

Clear seasonal patterns: peaks and dips repeat annually, indicating high and low seasons.
A gradual increase in guest arrivals over years, showing business growth.
Several spikes (>300 guests) indicate events, holiday seasons, or promotions.

Value Added:
Time-series analysis supports:

![Image](https://github.com/user-attachments/assets/23b952f5-f5b3-4c80-bf82-72a7a3a4a2f8)

Forecasting demand
Budget planning
Seasonal pricing
Resource allocation

![Image](https://github.com/user-attachments/assets/8994fe4a-456d-43c9-91c0-9ec3925e9302)

📌 7. KDE (Density) Plot – Guest Arrivals
This plot further confirms the normal-like distribution of arrivals, showing smooth density variations without noise from histogram bars.

![Image](https://github.com/user-attachments/assets/9931d178-20d5-4f02-99d5-8cd11d6f2e4d)
