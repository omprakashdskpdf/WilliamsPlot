# R-progrma for WilliamsPlot

 This R-program is for Williams plot based evaluation of Regression model for Applicability domain
 Written by: Dr. Om Prakash, UGC-DSKPDF/BL/15-16/0291, C/o Prof. U.N. Dwivedi, Department of Biochemistry, Lucknow University, India
 Package MASS needed R>=3.0.0 to run it
 The data must contain two sections, as following: 
 Descriptor matrix[nxN],Residual col[nx1] i.e. right-last column
 put the model's trainging data (i.e. descriptors & residual value) in train.csv named file in program path
 put the testing data (i.e. descriptors & residual value) in test.csv named file in program path
 For Unknown query compound, Put the residual value ZERO i.e. 0
 Get your output details in OutPutFile_LOG.txt & WilliamsPlot.jpg
 You can also print the plot by right-clicking on Graph generated
 Note: Your .csv must have numeric entries only
