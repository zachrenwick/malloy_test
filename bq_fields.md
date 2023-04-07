# Malloy BQ Table Field Descriptions
This data comes from BQ. Descriptions by field/column.

## What is this?

[Malloy Composer](https://github.com/malloydata/malloy-composer) is an open source tool for viewing and exploring data sets.  Data models are created in the  [Malloy](https://github.com/looker-open-source/malloy/) language.  Data can be served from a simple webserver or from a SQL database.  

See the [Malloy source code](https://github.com/zachrenwick/malloy_test/) 


## BigQuery Field Dashboard

See column description coverage by table and struct breakdown. Which tables have the best coverage of descriptions filled?

<!-- malloy-query  
  name="Field Dashboard: See column description coverage by table and struct breakdown"
  model="bq_fields.malloy"
-->
```malloy
  query: bq_fields -> bq_field2_dashboard
```

## Explore Other Queries

<!-- malloy-query  
  name="Query one"
  model="bq_fields.malloy"
-->
```malloy
  query: bq_fields -> missing_field_descriptions
```

<!-- malloy-query  
  name="Field Dashboard Two"
  model="bq_fields.malloy"
-->
```malloy
  query: bq_fields -> bq_field1_dashboard
```


## About Malloy Composer
Composer is implemented using Malloy, DuckDB and WASM and runs completely
in your browser.  Javascript code is compled from here:

  https://github.com/malloydata/malloy-composer