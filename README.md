# PysparkCode to convert multiline json to delimited file and normalize the nested tree structure to flat file.
The Structure of file source file is:

root
 |-- dataset: struct (nullable = true)
 |    |-- collapse: string (nullable = true)
 |    |-- column_index: string (nullable = true)
 |    |-- column_names: array (nullable = true)
 |    |    |-- element: string (containsNull = true)
 |    |-- data: array (nullable = true)
 |    |    |-- element: array (containsNull = true)
 |    |    |    |-- element: string (containsNull = true)
 |    |-- database_code: string (nullable = true)
 |    |-- database_id: long (nullable = true)
 |    |-- dataset_code: string (nullable = true)
 |    |-- description: string (nullable = true)
 |    |-- end_date: string (nullable = true)
 |    |-- frequency: string (nullable = true)
 |    |-- id: long (nullable = true)
 |    |-- limit: string (nullable = true)
 |    |-- name: string (nullable = true)
 |    |-- newest_available_date: string (nullable = true)
 |    |-- oldest_available_date: string (nullable = true)
 |    |-- order: string (nullable = true)
 |    |-- premium: boolean (nullable = true)
 |    |-- refreshed_at: string (nullable = true)
 |    |-- start_date: string (nullable = true)
 |    |-- transform: string (nullable = true)
 |    |-- type: string (nullable = true)
