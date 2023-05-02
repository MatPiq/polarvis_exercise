When analysing the content and usage of images in online political
communication, a natural first step (and potential end goal) is to group
similar images together, such that the groups operationalize some themes or
categories of relevance to the present study. This task is difficult for many
reasons, one of them being that if done manually by the researcher, it may be
very time consuming or even infeasible for large datasets. In this context, an
automated and computational method called
[clustering](https://en.wikipedia.org/wiki/Cluster_analysis) might be
interesting—not only as a way to assign images to categories, but also as a
tool for inductively *exploring* what categories may exist in the data. In
general, the objective of clustering methods is to create a partition of the
data into groups that are internally coherent and distinct from each other.
Exactly how this is achieved, differs between methods in e.g. by how the
distance or similarity between the objects being clustered is measured. An
important task, independent of what clustering method is used, is to
assess the validity of the results. 


!!! exercise "The task"
	In this exercise, we have prepared six different and fully automated
	*clusterings* of 150 images from the COP21 conference, collected as
	part of the *PolarVis* project. A clustering is the resulting
	assignment of images into clusters produced by one particular
	clustering method and set of
	[hyperparameters](https://en.wikipedia.org/wiki/Hyperparameter_(machine_learning))
	[^1]. The goal of this exercise is for you to explore the different
	clusterings, evaluate their quality and discuss the potential
	usefullness of these methods for discovery and measurement. This will
	be done by looking at the images and how they are placed in different
	clusters [here](../../clusterings/clusterings/).

	[^1]: Ainstru
	[hyperparameter](https://en.wikipedia.org/wiki/Hyperparameter_(machine_learning))
	is a value that is set prior to fitting the clustering method to the
	data and that controls or affects some aspect of learning from the
	data. In the context of clustering, the most important hyperparameter
	is typically the number of clusters (groups).



!!! info "Practicalities"
	**Timetable**

	|Content|Time|
	|-----|-----|
	|Intro to exercise|10.15-10:25|
	|Work on exercise in groups|10.25-11:10|
	|Discussion in plenum|11:10-11:30|

	**Groups**

	* Group 1: VY, ...
	* Group 2: MM, ...
	* Group 3: AS, ...

	**Important Links**

	* Questionarie for Q1 (individual exercise): <https://doit.medfarm.uu.se/bin/kurt3/kurt/92173>
	* Padlet for Q2 and Q3 (group exercise).
		* Group 1: <https://padlet.com/matiaspiqueras/group-1-vyhfrjhk6hwbhq0k>
		* Group 2:
		* Group 3:
	* Collective padlet for plenum discussion: 


!!! question "Questions"

	Below you will find a set of questions that we ask you to answer either
	individually (Q1) or in your groups (Q2 and Q3). Note that Q1 is also
	included in questionaire and Q2 and Q3 are in the group padlets (see
	important links).

	1. Based on your experience and understanding of the COP21 dataset:

	    1. What are the different themes that you expect to see in the images?
	    2. Do you expect some themes to be more or less prominent than
	       others? Which ones and why?

	2. Out of the six clusterings, select the one that you as a group think
	   is *best* and answer the following questions:
	    1. Why did you select this particular clustering? What implicit or
	       explicit criteria did you use to make your decision?
	    2. Try to interpret each cluster from the selected clustering and
	       if possible try to provide a label for each cluster. What
	       concepts do they operationalize? Are they scientifically
	       relevant?

	3. Cluster quality can be improved by bringing the researcher into the
	   loop and providing input to the clustering methods. This can nudge
	   the algorithms to better consider *your* particular research
	   objective, prior knowledge and domain expertise. 
	    1. For the selected clustering, what would you change (if
	       anything)? You could think in terms of individual images that
	       are *misplaced* or more broadly e.g. that some theme important
	       to you is missing.
	    2. In general, what kind of human input do you think would be
	       valuable to be able to provide?

