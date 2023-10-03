# API interaction project reflection


# Project links


I've just completed project [Vignette for reading and summarizing data from an IQAir APIs](https://npeshekncsu.github.io/st558-project2/). The project github repo is [github](https://github.com/npeshekncsu/st558-project2).


# Chosen API overview

The [IQAir APIs](https://api-docs.iqair.com/?version=latest&_gl=1*nxjz2i*_ga*MTE2NDM1MzcxNC4xNjk1Nzc5MTIx*_ga_L8T9FHWX08*MTY5NTc3OTExOS4xLjEuMTY5NTc3OTE4Ny41NS4wLjA.#important-notes) allow to retrive real-time air quality metrics in US EPA standard and China MEP standard for the selected city. In addition, APIs also provide current weather metrics, such as temperature, atmospheric pressure, wind speed and humidity.


# Project overview

In my project I've created several functions which allows easy interact with API and return data in easy to use format, such as lists or tibbles. Two main functions were created in the project:

  - function which allows to retrive air quality and weather metrics based on country, state and optional city. If city is not provided, random sample will be taken from the cities of the selected state
  - function which allows to retrieve air quality and weather metrics for the country. Random state and random city will be selected from the provided country.

Once functions were avaible,  EDA for data for several countries across the globe and data for the several US states were performed.




