# Ocean-Swell-Model

Accurate forecasting of future states in complex systems from time series data is a ubiquitous problem in many disciplines of engineering and science. We are interested in making predictions for time-dependent sequential data problems where we believe future states to be deterministically dependent on some previous sequence of states.

This project seeks to design and implement a recurrent neural network that can be applied to the time-series analysis of ocean swell events. The data we are analyzing is the spectral wave density dataset provided by the National Data Buoy Center and collected from [Station 46025](https://www.ndbc.noaa.gov/station_page.php?station=46025) off the coast of my hometown, Los Angeles, California. This data has been truncated to only include measurements from the calender year 2022.

Recurrent neural networks excel in modeling systems where the temporal dynamics are crucial to the qualitative behavior of the system. We will use this type of sequential model because cyclic network architectures can better capture the wave dynamics of the ocean’s shoreline to make predictions of future sequences of wave data.