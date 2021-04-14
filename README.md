This is a project that I worked on as an intern working for soundsensing, a startup company in Oslo.

### The Goal:
  To make sound embeddings of a large urban sound dataset, reduce dimensions, and see to what extent the data is distinguishable from one another. At the end, I created a graph which displayed the various groupings of the sounds now, showing clearly the effect being embedded had on the quality of the data.
  __________________________________________________________________________________________________________________
 ## Embeddings.ipynb 
 Here I use PCA and TSNE to reduce dimensionality and TSNE visualization to visualize the uncategorized urban sound data.
  
  ![image](https://user-images.githubusercontent.com/55637647/114767528-06224180-9d68-11eb-9658-4cdc23d5baaa.png)

##  soundEmbeddings.py 
Here we embed each sound file (compress the size) and save them each in their respective organized "folds" in a new folder as embedded sound files.  
