# Malloy BQ Table Field Descriptions
This data comes from BQ. Descriptions by field/column.

## What is this?

[Malloy Composer](https://github.com/malloydata/malloy-composer) is an open source tool for viewing and exploring data sets.  Data models are created in the  [Malloy](https://github.com/looker-open-source/malloy/) language.  Data can be served from a simple webserver or from a SQL database.  

See the [Malloy source code](https://github.com/zachrenwick/malloy_test/) 


## Explore Names

Use the dashboard below to compare a bunch of names. Change the filter to select different names.

<!-- malloy-query  
  name="Basic Query"
  model="bq_fields.malloy"
-->
```malloy
query: bq_fields -> by_table_bar_chart
```

## About Malloy Composer

Composer is implemented using Malloy, DuckDB and WASM and runs completely
in your browser.  Javascript code is compled from here:

  https://github.com/malloydata/malloy-composer