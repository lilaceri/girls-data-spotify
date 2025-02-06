# Interactive spotify 'wrapped' workshop 

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
2. click open in google colab button
3. download the files called "streaming history..."
4. create a code cell at the top of the page and paste:
`from google.colab import files`
`uploaded = files.upload()`
5. this should open a diaglogue box for you to upload the files you just downloaded
6. 
