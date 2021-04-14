This is a project that I worked on as an intern working for soundsensing, a startup company in Oslo.

The Goal:
  To make sound embeddings (shorten the sound file to 1s) of around 8000 larger sound files, and analyze what connections and similarities can be made with the embedded sounds, and the previous sound files, and find out whether the data given from sound embeddings is comparable to the full sound file. At the end, I created a graph which displayed the various groupings of the sounds now, showing clearly the effect being embedded had on the quality of the data.
  __________________________________________________________________________________________________________________
  Embeddings.ipynb - I used jupyter notebook to run snippets of the code to avoid loading the entire dataframe each time, and I also graphed the sound embeddings to show the relation between the different sound categories even though they're only small 1 second snippets of sound.
  
  ![image](https://user-images.githubusercontent.com/55637647/114767528-06224180-9d68-11eb-9658-4cdc23d5baaa.png)

  soundEmbeddings.py - I wrote this program to embed each sound file in the dataframe (around 8000) and save them each in their respective organized "folds" in a new folder as embedded sound files. The main challenge with this was optimizing the code so that it was fast and didn't too long to embed all of the files.
  
  
  
Technology and sources:

    Python
  
    jupyter notebook - perfect for running snippets of code
    
    sci-kitlearn - machine learning model
    
    openl3 - used for embedding the files
    
    pandas - used for the soundfile dataframe
    T-SNE Plot - used to put the multidimensional sound embeddings to a 2d graph
    
    soundfile dataframe - built on jonnor's soundfile dataframe where I embedded sounds from the urban sound kit.
    
    In this project I used a function from jonnor's master thesis (urbansound8k.sample_path()) from urbansound8k https://github.com/giobirkelund/ESC-CNN-microcontroller and also his soundfile dataframe to aid in the embedding process.
