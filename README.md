# Machine learning based load prediction

As power systems continue to grow, both in scale and in
complexity, the demand for power rises alongside, leading
to greater and more diversified demand. In order for utility
companies to maintain operational efficiency and continue to
provide power reliably, the task of accurately forecasting the
load at a given time becomes increasingly important so that
the various means for generation can be coordinated to satisfy
the demand.
Generally, the load forecasting is done over varying time
intervals because this helps the utilities plan their short term
investments and operations as well as gives them a basis
for proper judgement regarding longer term, capital-intensive
investments such as additional capacity and distribution in-
frastructure. These models help the electric utility companies
to make decisions about short term, medium term, and long
term decisions about operational and investment aspects of the
power system. A reliable method to make such short, medium
and long term forecasts is therefore crucial.
With more data becoming available through integration
of smart meters and other such measurement devices, it is
possible to implement better models. Several methods exist
for electric load forecasting using machine learning. We have
implemented 3 methods for load forecasting, namely Long
Short-term Memory (LSTM), Gated Recurrent Unit (GRU),
and Convolutional Neural Network (CNN). The models are
trained on the provided dataset of hourly usage data for 2
years. The data was then split into seasons, to aid prediction
during a particular season, as the average usage per day during
each season was different, as was the hourly distribution of the
usage
