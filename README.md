# WeddingWeather
### A (successful) optimization approach for our wedding date using Python and historic weather data.

In this Python Notebook I try to identify periods of constantly nice weather in Germany in the months of July-September. As my wife and I were setting a date for our wedding, we were wondering if some periods in summer are more stable than others, or if we should avoid certain periods at all.

These questions were motivated by the occurance of weather anomalies, i.e. reoccurring periods of good (or bad weather). The most prominent example in Germany is the "christmas melting weather" around Christmas day which often brings temperatures of about 15°C (and therefore no christmas-like weather).

For this work, we will use data from the German Weather Service (DWD) and the Climate Data Center [CDC] https://www.dwd.de/EN/climate_environment/cdc/cdc.html. We will use data from the meteorological station Clausthal-Zellerfeld, a city in the Harz mountains in central Germany (but any other station can be used). A list of avaible stations can be found in the [list of meteorological stations in Germany](https://www.dwd.de/DE/leistungen/klimadatendeutschland/statliste/statlex_html.html?view=nasPublication&nn=16102)

You can download the data set using 
```bash
wget https://opendata.dwd.de/climate_environment/CDC/observations_germany/climate/daily/kl/historical/tageswerte_KL_00863_18900101_20120331_hist.zip 
```
We eventually decided to have our wedding on August 4th. And yes, we were quite successful with our weather prediction as this day was a beautiful summer (and wedding) day.
