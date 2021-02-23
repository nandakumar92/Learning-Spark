Spark is unified - It has API's for analytics, streaming, machine learning all in one place.
Spark is focused on computation. It is storage independent and can be used on multiple storage databases platforms.

Spark has two main workers - Driver and Executor. Both are managed by cluster manager. Driver is like leader node and coordinated with user application 
and sends instructions to executors.

Spark Session - Spark session is the way Spark creates a session for the application to execute.

DataFrames - Spark dataframes are like python dataframes or spreadsheets except they store and execute across multiple machines.

Transformations - Spark transformations are the way Dataframes are modified and transformed.

Actions - Transformations build up logical plan. To trigger the computation, we run an action. An action instructs Spark to compute a result from a series of transformations.

