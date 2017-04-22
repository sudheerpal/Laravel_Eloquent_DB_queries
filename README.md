# Laravel_Eloquent_DB_queries
Collection of useful queries (Eloquent and DB )


### Fetching values from a column

$collection = DB::table('table_name')->where([
           ['field1', $value1],
           ['field2', $value2],
           ])->get();
           
// first()  is used when we need only first match in the collection.

// first() cant be used when there is only one record (unique record)
           
           
