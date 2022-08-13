# Data-Science-Portfolio
Here we showed some Bioinformatics data processing. Processing is very staright forward, 
just go ahead and run the cells. Also each code chunk is expalined by elaborated commments. Happy coding....

##### Here files are in .jason extension. Before running them on google colab rename them as .ipynb and work on them #######

Here we develop a Machine Learning project to find the active compunds which might have potency to inhibit coronavirus.

Part I - Preprocessing of the coronavirus inhibitor data imported from  CheMBL database.
We have demonstarted how to download and preprocess bilogical active data from the ChemBL database. The dataset are comprised of compounds that have been bilogically tested for their activity towards target organism or single protein molecule of interest.

Part II - Here we take the dataset from part 1 and use the SMILES notation to compute molecular descriptors. (before work on that download the preprocess data of part I from your google colab side bar and uplod during Part II. Copy the path of the data file. In the initial section we will find the four paramaters of the Lipinski rule of five by using Lipinki function. and in the second section we are going to do exploratory data analysis to see the statistical difference between active and inactive compounds.)

Here we have shown how to calculate lipniski descriptors (molecular descriptors propsed by Christopher Lipinski for predicting their likelihood of being drug-like molecules)

Part III - we will use data from Part II with pIC50 and gping to use prepare data with molecular fingerprints comparison data of the coumpounds and pIC50. which going to be used in Part IV. To compare molecular fingerprints of our compounds with pubchem fingerprints database we will use PADEL-Descriptor.

Here we prepare dataset (X and Y dataframes) that used in the part IV for model building

Part IV - we develop a ML model by using random forest to predict pIC50 of our compounds and compare them with the experimental pIC50

Lipinski rule of five ---> describe the global properties of the compounds which can give an idea of the druglikeliness of the compounds 

While fingerprint comparison provides the local feature of the compounds. If we consider a compund as combination of several lego blocks, each block can be responsible for unique behavior of that molecule. so fingerprint similarity shows the how similar or disimilar our compunds with the existing fingerprints database.

Her we have shown how to use computed molecular descriptors from Part III (as the X variables) to build a regression model for predicting the pIC50 values (the Y variable)

Part V - here we demonstarte how to quickly build and compare several regression models () of the coronavirus inhibitors using the lazypredict library in Python

While starting to work on a supervised learning problem, we are often not sure which models will work with the dataset at hand.
A possible solution would be to start with a model that works fairly well for many datasets i.e. Random forest and then iterate.  
Most likely, at some point in time you also considered throwing all the models at the dataset and just seeing what will happen. 
lazypredict is the handy library which can train all the models available in scikit-learn with single line of code. 


