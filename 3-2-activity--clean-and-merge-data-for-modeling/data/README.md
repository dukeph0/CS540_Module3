# About the data

# Weather Data Files

| File | Description | Source |
| --- | --- | --- |
| `earthquakes.csv` | Earthquake data from September 18, 2018 through October 13, 2018. |  The US Geological Survey (USGS) earthquake API. |
| `nyc_temperatures.csv` | Temperature data for New York City in October 2018 measured from LaGuardia airport, containing daily minimum, maximum, and average temperature. | The NCEI API's GHCND dataset |
| `nyc_weather_2018.csv` | Long format weather data for New York City across various stations. | The NCEI API's GHCND dataset. |
| `parsed.csv` | Data from `earthquakes.csv` with an additional column for the location (parsed from the data to handle multiple names for the same entity). |  The US Geological Survey (USGS) earthquake API. |
| `quakes.db` | A SQLite database of a single table, `tsunamis`, which contains all data on the earthquakes in `earthquakes.csv` that were accompanied by a tsunami. |  The US Geological Survey (USGS) earthquake API. |
| `tsunamis.csv` | Data for all earthquakes in `earthquakes.csv` that were accompanied by a tsunami. |  The US Geological Survey (USGS) earthquake API. |
| `weather_by_station.csv` | Long format weather data for New York City across various stations, along with station information. | The NCEI API's GHCND dataset and the `stations` endpoint. |
| `weather_stations.csv` | Information on all the stations providing weather data for New York City. | The NCEI API's `stations` endpoint. |
| `weather.db` | The `weather` table contains New York City weather data, while the `stations` table contains information on the stations. | The NCEI API's GHCND dataset and the `stations` endpoint. |
