# Fire-Forest-hazard-clustering

The last summer the world was shocked by the incredibly massive wildfires spreading all over the world. Canada, Greece and Syberia are just some of the countries who have suffered with enourmus area wiped out by the fire. Every year wildfires spread with increasing power and frequency.

The main aim of this project is to study the evolution of the wildfire hazard in Europe trough machine learning clustering techniques. We will see that in the last 5 years the climate and geological condition of Europe are harsher than ever.

The repository is divided into by three parts:

1. **Cleaning data:** we take the data published from the Copernicus Emergency Management Service (available on the 'data' folder) and select the information relative to the european region.
2. **Exploratory Data Analysis:** here we explore the dataset  (focusing on spatial and time dependences) obtaining the first insights that we will observe with our machine learning model.
3. **Machine learning model:** in the last part we build our machine learning model, that consists in a combination of unsupervised and supervised techniques. First, we adopt Kmeans clustering to define 4 regions based on the wildfires hazard, then we train a random forest classifier in order to recognize these labels. Finally, we have a model that is capable to classify the regions whereby the danger of large and catastrophic wildfires are more probable.

To run the notebooks you **must first download the data folder** available here: https://drive.google.com/drive/folders/17IF_QRzRcMgrlMnupTvyUhfwbSaJbPnt?usp=sharing
