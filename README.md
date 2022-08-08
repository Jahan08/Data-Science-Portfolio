# Data-Science-Portfolio
Here we showed some Bioinformatics data processing. Processing is very staright forward, 
just go ahead and run the cells. Also each code chunk is expalined by elaborated commments. Happy coding....

Here we develop a ML project to find the active compunds which might have potency to inhibit coronavirus.

Part I - Preprocessing of the coronavirus inhibitor data imported from  CheMBL database.

Part II - Here we take the dataset from part 1 and use the SMILES notation to compute molecular descriptors. (before work on that download the preprocess data of part I from your google colab side bar and uplod during Part II. Copy the path of the data file. In the initial section we will find the four paramaters of the Lipinski rule of five by using Lipinki function. and in the second section we are going to do exploratory data analysis to see the statistical difference between active and inactive compounds.)

Part III - we will use data from Part II with pIC50 and gping to use prepare data with molecular fingerprints comparison data of the coumpounds and pIC50. which gping to be used in Part IV. To compare molecular fingerprints of our compounds with pubchem fingerprints database we will use padel.

Part IV - we develop a ML model to predict pIC50 of our compounds and compare them with the experimental pIC50


Lipinski rule of five ---> describe the global properties of the compounds which can give an idea of the druglikeliness of the compounds 

While fingerprint comparison provides the local feature of the compounds. If we consider a compund as combination of several lego blocks, each block can be responsible for unique behavior of that molecule. so fingerprint similarity shows the how similar or disimilar our compunds with the existing fingerprints database.

##### Here files are in .jason extension. Before running them on google colab rename them as .ipynb and work on them #######
