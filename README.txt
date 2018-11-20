https://github.com/davidjianfeng/unsupervised-learning.git


0.	The folder has two main codes: one for part 1, the other for part 2, and two subfolders
Part 1:
	continuouspeaks.py
	travelingsalesman.py
	flipflops.py

Part 2:
	NN_dataProcessing.py
	NN_BP.py
	NN_GA.py
	NN_RHC.py
	NN_SA.py

	Shared folders
	.\ABAGAIL
	.\Datasets\Bankloan_data


1.	To run the code and load the data, someone needs to change the working director path to the folder where the all the data files are unzipped . 

### part 1 example ###  
	sys.path.append("C:/Users/HP/Desktop/classes/GT/HW2/ABAGAIL/ABAGAIL.jar")
	outfile = 'C:/Users/HP/Desktop/classes/GT/HW2/CONTPEAKS/CONTPEAKS_@ALG@_@N@_LOG.txt'

### part  2 example ###  
	sys.path.append("C:/Users/HP/Desktop/classes/GT/HW2/ABAGAIL/ABAGAIL.jar")
	OUTFILE = 'C:/Users/HP/Desktop/classes/GT/HW2/NN_OUTPUT/BACKPROP_LOG.txt'

        training_ints = initialize_instances('C:/Users/HP/Desktop/classes/GT/HW2A/Datasets/b_trg.csv')
        testing_ints = initialize_instances('C:/Users/HP/Desktop/classes/GT/HW2A/Datasets/b_test.csv')
        validation_ints = initialize_instances('C:/Users/HP/Desktop/classes/GT/HW2A/Datasets/b_val.csv')
  

2.	for Part 2, NN_dataProcessing.py needs to run first. 

Notes:
1.	To run the code, someone needs to change the working director path to load the data. Some intermediate results are outputted previously as objects and are loaded in the code to save running time. 
2.	https://github.com/pushkar/ABAGAIL
3.	https://github.com/JonathanTay  (reference codes for this homework)