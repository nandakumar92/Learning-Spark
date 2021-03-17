https://www.amazon.com/Spark-Definitive-Guide-Processing-Simple/dp/1491912219/ref=sr_1_2?crid=3V35RBFJCV5UP&dchild=1&keywords=spark+definitive+guide&qid=1616019317&sprefix=spark+defini%2Caps%2C243&sr=8-2

<h1>Chapter 1</h1>

* Spark is unified - It has API's for analytics, streaming, machine learning all in one place.
* Spark is focused on computation. It is storage independent and can be used on multiple storage databases platforms.
* Spark has two main workers - Driver and Executor. Both are managed by cluster manager. Driver is like leader node and coordinated with user application 
  and sends instructions to executors.
* Spark Session - Spark session is the way Spark creates a session for the application to execute.
* DataFrames - Spark dataframes are like python dataframes or spreadsheets except they store and execute across multiple machines.
* Transformations - Spark transformations are the way Dataframes are modified and transformed.
* Actions - Transformations build up logical plan. To trigger the computation, we run an action. An action instructs Spark to compute a result from a series of transformations.
* Spark creates transformations in lazy manner, it will not execute until action is triggered. It will create explain plan unitl then.

<h1>Chapter 2</h1>

* Spark has low level api - RDD's , distributed variables , structured high level apis - spark sql, datrames, datasets . Higher libraries for streaming , ml ..etc. 

![image](https://user-images.githubusercontent.com/28901283/111545580-8470d100-8733-11eb-9376-9677db06b600.png)

