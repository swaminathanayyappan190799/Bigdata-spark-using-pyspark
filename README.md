
# Big data using pyspark with python

The volume of data that is generating nowadays is huge, as it may be of any kind structured,unstructured. Apache spark is one of the framework which will be very helpful and effective in handling big data, though there were other frameworks like hadoop but spark is 10x more effecient than the hadoop/HDFS.

   Apache spark is a cluster based architecture framework which has master and worker nodes (a distributed file system).It is faster,fault-tolerance i.e., even if one worker node goes down you will get your data from other worker nodes since it is replicated.
   






## Tools/softwares used

We may need a huge setup to handle big-data in the real world scenario.Since spark is a distributed framework it must have atleast one master and two worker nodes. Inorder to do this there are lot may services like databricks, AWS EMR, AWS EC2 was available in the market.Some of them were paid service like EC2 and EMR, whereas if you choose databricks selecting the community edition will be available at free of cost, and you can create one cluster per notebook. 

The volume of data that i used on this repository is very less, that's why i had installed spark on my local machine where it only has only one cluster to perform spark related operations.

For this task, i would recommend the following tools and softwares for the better functionality and running of the code.

1) Python (Using package installer/anaconda installer)
2) Visual Studio Code (as an IDE)
3) Jupyter notebook
## Installation

Apache spark was built using Java and Scala. Many programming languages like Python,R,Java and Scala has an extensive support for spark framework. In this repository we will use Pyspark, a python spark library used to access spark functions.

As an initial process, you have to install python  from python.org or using anaconda distribution. I have used anaconda distribution since it will be more comfortable in creating environments. I will suggest you people to follow the same. Moreover, the below procedures will be more similar if you install python in any one of the ways that i mentioned earlier.

Use anaconda prompt for performing the step 1 and 2

1) Creating Conda Environment


```anaconda prompt
conda create -n spark-env python==3.8.10 -y
```

Here, spark-env is the name of the python environment and wer'e using 3.8.10 version of python for this virtual environment.You can use any environment name and python version.

2) Activate the spark-env and install Pyspark

```anaconda prompt
conda activate spark-env
```
Once if you execute this command on your anaconda prompt, the environment will be changed from base to spark-env. After that install Pyspark using the below command.
```anaconda prompt
pip install pyspark
```
This command will let you install the latest version of pyspark along with it's dependencies.


## Authors

- [Swaminathan ayyappan](https://github.com/swaminathanayyappan190799)

