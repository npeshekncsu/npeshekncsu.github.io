# API interaction project reflection


# Project links


I've just completed project [Vignette for reading and summarizing data from an IQAir APIs](https://npeshekncsu.github.io/st558-project2/). The project github repo is [github](https://github.com/npeshekncsu/st558-project2).


# Chosen API overview

The [IQAir APIs](https://api-docs.iqair.com/?version=latest&_gl=1*nxjz2i*_ga*MTE2NDM1MzcxNC4xNjk1Nzc5MTIx*_ga_L8T9FHWX08*MTY5NTc3OTExOS4xLjEuMTY5NTc3OTE4Ny41NS4wLjA.#important-notes) allow to retrive real-time air quality metrics in `US EPA standard` and `China MEP standard` for the selected city. In addition, APIs also provide current weather metrics, such as `temperature`, `atmospheric pressure`, `wind speed` and `humidity`.


# Project overview


In my project, I've created several functions that allow easy interaction with the API and return data in an easy-to-use format, such as `lists` or `tibbles`. The project includes two main functions:

  - A function that allows the retrieval of air quality and weather metrics based on country, state, and an optional city. If a city is not provided, a random sample will be taken from the cities of the selected state.
  - A function that allows the retrieval of air quality and weather metrics for the entire country. A random state and city will be selected from the provided country.

Once the functions were available, exploratory data analysis (EDA) was performed on data from several countries worldwide and data from several U.S. states.



# Project reflection

I really enjoyed working on this project. I've learned a lot about building GitHub Pages. However, I did encounter some challenges during its development. One of the major challenges was selecting an API that met the project's requirements. In the future, I would consider choosing a different API because the one I selected returns data per city, which is not convenient for constructing a large sample.




