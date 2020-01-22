This is a project that I worked on while working for soundsensing, a startup company in Oslo.

The Goal:
  To make sound embeddings (shorten the sound file to 1s) of around 8000 larger sound files, and analyze what connections and similarities can be made with the embedded sounds, and the previous sound files, and find out whether the data given from sound embeddings is comparable to the full sound file. At the end, I created a graph which displayed the various groupings of the sounds now, showing clearly the effect being embedded had on the quality of the data.
  
Technology and sources:
    Python
    jupyter notebook - perfect for running snippets of code
    sci-kitlearn - machine learning model
    openl3 - used for embedding the files
    pandas - used for the soundfile dataframe
    soundfile dataframe - built on jonnor's soundfile dataframe where I embedded sounds from the urban sound kit.
    In this project I used a function from jonnor's master thesis and also his soundfile dataframe to aid in the embedding process.
