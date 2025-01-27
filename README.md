This project is helpful for finding molecular similarity based on SMILES representation and molecular descriptors. 
I know the basics of this model through which I built the code.
The difficult part was to convert the SMILES representations to fingerprints where I took help of gpt but understood what I was doing while writing the code.
First we import the data and then specify features and targets.
Then we convert the SMILES representation to to numerical data using rdkit which is useful for working with chemical informatics.
Then we write the basic code for the Random Forest Operator, use the test_train_split function to segregate the data into test data and train data.
We calculate the errors and plot the graph using matplotlib for easier visualizations.
