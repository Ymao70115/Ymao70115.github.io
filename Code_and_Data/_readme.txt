
	CONTENTS OF THIS FILE
	------------------------------------

	 * Introduction
	 * Recommended 
	 * Files 
 	 * Run the code



	INTRODUCTION
	------------------------------------
	This is the project for COMP 5704:  Parallel Algorithms and Application in Data Science.

	The project title: 
		Parallel Computing on Depression Analysis

	Student Information:
       		Yanan Mao, Carleton University, yananmao@cmail.carleton.ca



	RECOMMENDED 
	------------------------------------
	Strongly recommend running the files on CoLab with or without GPU.
	(Go to Edit -> Notebook Settings -> Hardware Accelerator -> drop-dowm mean: GPU)



	FILES
	------------------------------------
	The Datasets folder contains the required .csv files for this project:
		Upload all the .csv files when required.

	The Ipynb folder contains the COMP5704_project.ipynb files for this project.
		



	RUN THE CODE
	------------------------------------
	The project is divided into four sections:
		1. Import section: 
			Import libraries and upload all the .csv files when required.

		2. Processing dataset section: 
			Select the first subsection named: "Depression data(Test)" and one of the following subsections titled "Diabetes data, "Heart data," "Breast Cancer data"， and "Depression data(Train)". 
			This is because the rest of the dataset are sources domain, and they own the same variable names. 
			Multiple selections will not crash the network, but only the last choice will be counted as the source domain in the following sections. 
			In other words, multiple results could be obtained only by selecting one source domain dataset and running the rest two sections. 
			The accuracy of the whole project will be saved in the scores array.

		3. Functions section:
			Transfer learning and Parallel K-means methods will be applied in this section. Run the cells without hesitation. The outputs are available to check anytime. 

		4. Results section:
			Plot the graphs, vividly showing the results. The plot title must be changed manually, but the graph will not be influenced. For result observation, the name could be ignored.  
