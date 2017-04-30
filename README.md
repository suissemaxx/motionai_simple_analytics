# motionai_simple_analytics
Simple analytics with Motion AI CSV reports

Bot reports (CSV or JSON) from motion.ai can get very heavy up to the point where Excel simply can´t handle the file size any more. This notebook uses [Pandas](http://pandas.pydata.org/) to ingest even very large CSVs and spits out some basic stats, charts by day and hour as well as sorted top lists for modules and user messages.

The easiest way of using this notebook is by installing [Anaconda](https://www.continuum.io/downloads) which comes with the required Numpy, Pandas and Matplotlib libraries.
