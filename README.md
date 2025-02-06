# Interactive spotify 'wrapped' workshop 

This repo contains an interactive workshop designed to be delivered to secondary school age children/young adults. It provides a worksheet and sample data that students can use to simulate Spotify's Wrapped using python to analyse spotify listening history, create a variety of visualisations and a simple machine learning model.

### Instructions
---
1. clone repo
2. open ipynb
3. linked data in this repo
4. complete worksheet

*congrats you are now a Data Scientist*

### How to use own data
---
1. Go to Spotify.com and login - heres some more info https://support.spotify.com/us/article/understanding-my-data/
2. Wait up to a week for download link
3. Download your data
4. Replace sample data with your own

### Detailed instructions for laptop set up

1. Download Anaconda
2. Set up conda environment to have python & jupyter labs
3. Open jupyter labs
4. Open console
5. `conda install anaconda::git`
6. `git clone https://github.com/lilaceri/girls-data-spotify.git`
7. cd into the folder you've just cloned - soemthing like `cd girls-data-spotify`
8. `python -m pip install -r requirements.txt`
9. Open ipynb and check it runs ok - you may need to uncomment some of the !pip package installs in the first code cell

### Detailed instructions for google Colab
1. open spotify wrapped ipynb on this browser
2. click open in google colab button at the top
3. notebook should run using the provided data on this repo - make sure to run the 3 hidden cells
4. if you want to use your own data - try to write a function to do this and change the `dfs = get_local_filepaths()`
   to `dfs = your_function()`
   
