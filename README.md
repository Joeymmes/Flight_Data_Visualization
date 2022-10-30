# Airline on-Time Performance Data
## by Joseph Ebere


## Dataset

>  The dataset name is "Airline On-Time Performance Data". This dataset reports flights in the United States, including carriers, arrival and departure delays, and reasons for delay, from 1987 to 1989. Some columns contained in the dataset were really not important for the exporation, therefore, such columns were dropped. Three years of data were loaded and merged together inot a master dataframe "flights". NAN cells were replaced withzero in order not to drop the rows that contained it, thereby loosing some information the dropped rows might contain.

The features of interest in the dataset are;

> **Actual Arrival Times (ArrTime):** is the instance when the pilot sets the aircraft parking brake after arriving at the airport gate or passenger unloading area.

> **Actual Departure Times (DepTime):** is the instance when the pilot releases the aircraft parking brake after passengers have loaded and aircraft doors have been closed.

> **Arrival Delay	(ArrDelay):** Arrival delay equals the difference of the actual arrival time minus the scheduled arrival time. 

> **CRS Computer Reservation System.** CRS provide information on airline schedules, fares and seat availability to travel agencies and allow agents to book seats and issue tickets.

> **Cancelled Flight (Cancelled):**	A flight that was listed in a carrier's computer reservation system during the seven calendar days prior to scheduled departure but was not operated.

> **Departure Delay (DepDelay):** The difference between the scheduled departure time and the actual departure time from the origin airport gate.

> **Diverted Flight (Diverted):** A flight that is required to land at a destination other than the original scheduled destination for reasons beyond the control of the pilot/company.

> **Elapsed Time (for CRSElapsedTime & ActualElapsedTIme):** The time computed from gate departure time to gate arrival time.


> **Scheduled Departure Time (CSRSDepTime):** The scheduled time that an aircraft should lift off from the origin airport.

> **Scheduled Time Of Arrival (CRSArrTime):** The scheduled time that an aircraft should cross a certain point (landing or metering fix).

> **Unique Carrier (unique):** Unique Carrier Code. It is the Carrier Code most recently used by a carrier. A numeric suffix is used to distinguish duplicate codes, for example, PA, PA (1), PA (2). Use this field to perform analysis of data reported by one and only one carrier.


## Summary of Findings

> For the feature "Origin", the investigation shows that the origin(Cities): ORD, ATL, DFW, LAX, DEN have the highest frequency of flights going out of them and this trend is the same for the three years under consideration (i.e 1987, 1988, 1989).

> For the feature "Dest", which represents the destination cities, the same cities ORD, ATL, DFW, LAX and DEN have the highest frequency of flights arrival, and this trend is the same for the years under consideration (1987, 1988, 1989).

> The destinations; ORD, ATL, DEN, LAX, SFO; are home to more cancellations and the trend is the same for the three years under consideration.

> Week days like Monday, Tuesday and Wednesday have a consistent lower level of delays and cancellation across the three years under consideration.

## Key Insights for Presentation

> Weekdays like Monday, Tuesday, Wednesday have a consistent lower level of delays and cancellation across the tree years under consideration. This trend can be attributed to different factors like urgency of travel, lower flights traffic etc

> Some destinations like; ORD, ATL, DEN, LAX, SFO; are home to more cancellations and the trend is the same for the three years under consideration. Therefore, a person that wishes to travel to or from this locations needs to make proper arrangement to ensure that the travelling day do not also falls within the days prone to flight delays and cancellation.