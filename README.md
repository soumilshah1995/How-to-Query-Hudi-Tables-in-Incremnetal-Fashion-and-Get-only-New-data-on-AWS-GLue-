
How to   Query  Hudi Tables in Incremnetal Fashion and Get only New data on AWS GLue 
![Capture](https://github.com/soumilshah1995/How-to-Query-Hudi-Tables-in-Incremnetal-Fashion-and-Get-only-New-data-on-AWS-GLue-/assets/39345855/bf5f0e51-2bcd-4f66-bad4-41915df690ba)


```

--additional-python-modules  | faker==11.3.0

--conf                        |  spark.serializer=org.apache.spark.serializer.KryoSerializer  --conf spark.sql.hive.convertMetastoreParquet=false --conf spark.sql.hive.convertMetastoreParquet=false --conf spark.sql.catalog.spark_catalog=org.apache.spark.sql.hudi.catalog.HoodieCatalog --conf spark.sql.legacy.pathOptionBehavior.enabled=true --conf spark.sql.extensions=org.apache.spark.sql.hudi.HoodieSparkSessionExtension

--datalake-formats            | hudi
```
