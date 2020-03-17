# Notebooks Directory

This directory contains the main work of this project, mostly in Jupyter notebooks, but also some python and bash scripts.

## Directory Structure

```
.
├── Exploratory_Analysis
├── Getting_the_Data
├── Modeling
└── README.md
```


## Outline

* *Exploratory Analysis*

> This directory contains the code that was used to find duplicate songs, visualize missing data, and perform some telling exploratory data analysis.

* *Getting the Data*

> This directory contains the code used to gather the information needs to create my final dataframe. I utilized Spotify's API by being able to pull songs and playlists, specified by amount of followers and the music genre. The repository shows when I started to get accustomed to the API, pulling single songs, playlists, and audio features. Then, I progressed into creating functions to pull certain playlist ID's dependent on number of followers and music genre. Finally, I wrote a function that would get all the features I needed from each song in this music genre. Lastly, was able to process and transfer all of my data into the form I wanted, a clean .csv final. I used this static datset for modeling. 

This directory contains notebooks and a scripts pertaining to data analysis and processing, specifically important considering the specialized nature of the LaTeX in the text being processed
This directory also contains the scripts for transforming the text into GloVe vectors which will be used to comparing articles.

* *Modeling*

> This directly contains the notebooks which are used to model song popularity. Ranging from linear regression to neural networks, the code shows all of my metrics and how I performed analysis. 
