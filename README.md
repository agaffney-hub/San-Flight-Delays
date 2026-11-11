# San Diego Flight Delay Analysis & Prediction

## Project Overview

San Diego International Airport (SAN) serves more than 25 million passengers annually, making it the busiest single-runway airport in the United States. Operating with a single runway and an overnight departure curfew from 11:30 p.m. to 6:30 a.m., SAN faces unique operational constraints that make understanding flight delays particularly important.

This project investigates the factors influencing flight departures and arrivals at SAN by combining aviation, aircraft, and weather data from three federal agencies:

- **[Bureau of Transportation Statistics (BTS)](https://www.transtats.bts.gov/ontime/):** Airline on-time performance, flight schedules, departure and arrival times, and delay information.
- **[Federal Aviation Administration (FAA)](https://www.faa.gov/licenses_certificates/aircraft_certification/aircraft_registry/releasable_aircraft_download):** Aircraft registration and aircraft make, model, and series information.
- **[National Oceanic and Atmospheric Administration (NOAA)](https://www.ncei.noaa.gov/cdo-web/):** Historical weather observations, including temperature, precipitation, and wind conditions.

The SD Crew will integrate these datasets into a structured SQL database to support connected queries and further analysis. Using Python, the project will examine departure and arrival patterns across airlines, aircraft models, taxi-out times, and weather conditions.

Exploratory data analysis and machine learning techniques, including k-means clustering, logistic regression, and gradient boosting, will be used to investigate operational patterns and develop predictive models. A primary objective is to identify which departing flights are likely to experience delays exceeding 15 minutes.

Ultimately, this project aims to transform complex aviation data into meaningful insights, improve transparency surrounding flight delays, and provide San Diego travelers with a better understanding of the factors affecting their journeys.

## References

1. [SAN Airport Authority: About the Authority](https://www.san.org/about-the-authority/)
2. [SAN Airport: Airport Facts and History](https://www.san.org/about-the-authority/history-of-san/)
3. [SAN Airport: Aircraft Noise and Departure Curfew](https://www.san.org/aircraft-noise/)
4. [BTS: Airline On-Time Statistics](https://www.transtats.bts.gov/ontime/)
5. [FAA: Aircraft Registration Database](https://www.faa.gov/licenses_certificates/aircraft_certification/aircraft_registry/releasable_aircraft_download)
6. [NOAA: Climate Data Online](https://www.ncei.noaa.gov/cdo-web/)
