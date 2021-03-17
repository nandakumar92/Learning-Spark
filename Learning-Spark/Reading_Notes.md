
https://www.amazon.com/Learning-Spark-Jules-Damji/dp/1492050040/ref=sr_1_1?crid=28DDHCJ6ZI78X&dchild=1&keywords=learning+spark&qid=1616020043&sprefix=learning+spar%2Caps%2C241&sr=8-1

<h1>Chapter 2</h1>
  
  * At the core of spark application is the spark driver program which creates the sparksession. 
  * Sparksession is the entry point to run the application via tasks through executors(nodes)
  * Spark driver is part of the shell (spark-shell in scala or pyspark shell in python). Sparksession is inititated when shell is called.
  ![image](https://user-images.githubusercontent.com/28901283/111547441-65c00980-8736-11eb-8b57-dce291de5a11.png)
  * During runtime, spark driver converts program into sparkjobs. Each sparkjob is converted to a DAG.
  ![image](https://user-images.githubusercontent.com/28901283/111547672-b9caee00-8736-11eb-9b54-7f332309a16d.png)
  * As part of DAG, spark can pujsh jobs in different stages. The stages finally have a task which run on an executor. 
  * Each task runs on one core, so 16 core executor can process 16 tasks parallely on 16 partitions of data.
  ![image](https://user-images.githubusercontent.com/28901283/111548326-c69c1180-8737-11eb-9133-b1d3851f779d.png)
  * Transformations - These are function such as select or filter which do not modify original data. 
  * Actions - None of the transformations are executed until either the user reads or there is a action such as count() in the application.
  ![image](https://user-images.githubusercontent.com/28901283/111548555-1ed31380-8738-11eb-86ac-952ea3f9532e.png)
  * Transformations can be of two types - Narrow and Wide
  * Narrow transformations run on single partition and produce singe output - example filter operation.
  * Wide transformation use data output from multiple partitions to produce output - groupby operation.
  ![image](https://user-images.githubusercontent.com/28901283/111548819-86895e80-8738-11eb-93cc-8a28203b6b6d.png)
  
 <h1>Chapter 3</h1>





  
 
