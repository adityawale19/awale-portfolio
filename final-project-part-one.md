 [final project I](final-project-part-one) 
# The Delay Domino Effect

### *How Flight Delays Build Throughout the Day*
## Outline
Millions of flights move through the U.S. aviation network every year, but a flight does not operate in isolation. An aircraft arriving late at one airport may depart late on its next flight, potentially carrying that delay into another city. This project will explore how flight delays change throughout the day and whether disruptions appear to accumulate as the day progresses.

Using U.S. domestic flight performance data, I plan to examine how departure delays vary by time of day, airport, and cause. Rather than focusing only on which airlines or airports have the most delays, the project will follow the aviation system from morning to night and investigate whether travelers flying later in the day experience a system carrying the effects of earlier disruptions.

## Initial sketches
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/e46d415c-d551-4b93-a2e2-53938f12e615" />
Sketch 1 shows how average departure delays change throughout the day, highlighting whether delays gradually build from morning into the evening.

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/5f1386bd-ac23-4ffa-bfe0-477a6dda7cc8" />
Sketch 2 shows how different causes contribute to delays throughout the day, with late-arriving aircraft potentially becoming a larger factor as delays accumulate.

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/70dac542-9d9b-42ca-830e-da106e88dd4f" />
Sketch 3 compares delay patterns across major airports to show how the timing and severity of delays can vary by location.

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/84d58d3a-7e27-4cc3-9fbc-6e296ed0dda4" />
Sketch 4 translates the delay patterns into a traveler’s perspective by comparing the likelihood and severity of delays across morning, afternoon, and evening flights.

## The data
The primary data source for this project will be the U.S. Department of Transportation, Bureau of Transportation Statistics (BTS) On-Time Performance dataset. The dataset contains detailed information on domestic U.S. flights, including scheduled and actual departure and arrival times, departure and arrival delays, origin and destination airports, cancellations, and flight characteristics. BTS also provides information about the causes of delays, including carrier, weather, National Airspace System (NAS), security, and late-arriving aircraft.

For this project, I plan to focus on a recent full year of flight data and use the scheduled departure time to group flights by hour of the day. I will examine how delays change from morning to evening, compare patterns across major U.S. airports, and investigate how different causes contribute to delays throughout the day. In particular, the late-arriving-aircraft category will help explore whether delays from earlier flights may contribute to delays later in the day. The analysis will eventually be used to create the line charts, heatmaps, and delay-cause visualizations shown in my initial sketches.

>

| Name | URL | Description |
|------|-----|-------------|
| BTS On-Time Performance Data | [BTS On-Time Performance](https://www.transtats.bts.gov/ONTIME/) | U.S. domestic flight-level data containing scheduled and actual flight times, airports, delays, cancellations, and other operational information. |
| BTS Airline On-Time Statistics | [BTS Delay Causes](https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp) | BTS data on flight delays and reported delay causes, including carrier, weather, NAS, security, and late-arriving aircraft. |


## Method and medium
I plan to use Tableau to analyze and visualize the flight performance data and Shorthand to create the final interactive story. Tableau will be used to develop the time-series, airport comparisons, heatmaps, and delay-cause visualizations. Shorthand will provide the narrative structure, allowing the reader to move through a typical day in the U.S. aviation system from early-morning operations to the accumulation of delays later in the day.

## References

* U.S. Department of Transportation, Bureau of Transportation Statistics. Airline On-Time Performance Data. [BTS TranStats](https://www.transtats.bts.gov/ONTIME/)
* U.S. Department of Transportation, Bureau of Transportation Statistics. Airline On-Time Statistics and Delay Causes. [BTS Delay Causes](https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp)

## AI acknowledgements
_*AI assistance was used to convert my basic visualization sketches and ideas into cleaner, more developed visual concepts. The project topic, story structure, visualization ideas, and final design decisions were reviewed and directed by me._
