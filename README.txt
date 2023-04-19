# BPepAMPred_Server
BPepAMPred server is a user-friendly and open-sourced deep learning model developed at Division of Agricultural Bioinformatics, ICAR-Indian Agricultural Statistics Research Institute, New Delhi. Bidirectional Gated Recurrent Unit (GRU) model has been deployed in a web server named BPepAMPred i.e., black pepper antimicrobial peptide prediction server with other hyper parameters for classifying antimicrobial peptides (AMPs) from non-antimicrobial peptides in black pepper. It can be accessed using http://login1.cabgrid.res.in:5040/ for the classification. Or, one can also run locally with following steps:
1. Download Pycharm using Download PyCharm: Python IDE for Professional Developers by JetBrains and install in the local system
2. Copy the entire folder in C:\\Users\Usr\PycharmProject
3. Install the following package using the following commands:
	a. pip install biopython
	b. pip install numpy
	c. pip install xlsxwriter
	d. pip install pandas
	e. pip install tensorflow
	f. pip install keras
	g. pip install sklearn
	h. pip install flask
	
4. Now run the app.py file using “python app.py” command
