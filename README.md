# Land value regression problem:
### Problem statement:
Based on the dataset of real estate transactions carried out on the entire French territory since 2014, we want to be able to create a model that predicts value / unit area. 
### Method:
For this problem, we're using a k Nearest Neighbor regressor algorithm. The features are the land coordinates and the label is value / area.
### Challenges:
The data is unknown to the author. I need to learn the data myself first to be able to create a suitable model.

## Data
There are three files associated with this problem:
1. **valeursfoncieres-2020.txt**, which includes all the real estate transactions carried out in the French territory since 2014. This file does not include geographical coordinates, but it does include land value and parsed IDs of the land.
2. **parcelles.zip**, which includes the geographical information (coordinates) of the lands, followed by the land ID which can be used to match with the land value in the text file.
3. **notice-descriptive-du-fichier-dvf-20210809_EN.pdf**, which is a text, explaining the data inside the txt file. 
