# Apache Spark in Microsoft Fabric

PySpark = Python + Apache Spark

It lets you process huge datasets (gigabytes to terabytes) across multiple machines, using Python code that looks similar to Pandas.

•Pandas is ideal for single-machine, in-memory analytics. 
•	PySpark is designed for distributed computing and massive datasets.
•	PySpark uses Spark’s optimized execution engine (Catalyst, Tungsten) for large-scale performance.

 Why PySpark matters (especially for Fabric) ?
 
•Since Microsoft Fabric uses Apache Spark under the hood, PySpark becomes the main language for:

•	Transforming data in Lakehouses
•	Building ETL pipelines
•	Writing Delta tables
•	Optimizing large datasets
•	Running notebooks at scale

I followed video from YouTube - https://www.youtube.com/watch?v=4aYKegIC6S0&list=LL&index=1&t=2783s  

# Best Practices - 

1) Dont try to break the pyspark parllelism split feature and try save data in single file
2) Use Tempview(this exists only till that session) tables if you want to register any table in order to split between processing language like from pythont to SQL.

• You can view how I worked on Pyspark in MSFabric in the video link below.

https://youtu.be/9pHoFAFVaqE 
