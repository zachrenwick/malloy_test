# Malloy BQ Table Field Descriptions
This data comes from BQ. Descriptions by field/column.

## What is this?

[Malloy Composer](https://github.com/malloydata/malloy-composer) is an open source tool for viewing and exploring data sets.  Data models are created in the  [Malloy](https://github.com/looker-open-source/malloy/) language.  Data can be served from a simple webserver or from a SQL database.  

See the [Malloy source code](https://github.com/zachrenwick/malloy_test/) 


## Explore BigQuery Field Descriptions

Use the dashboard below to compare a bunch of names. Change the filter to select different names.


<!-- malloy-query  
  name="Missing Description Columns"
  model="bq_fields.malloy"
-->
```malloy
query: bq_fields -> missing_field_descriptions
```

## About Malloy Composer

```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```
^above mermaid test


Composer is implemented using Malloy, DuckDB and WASM and runs completely
in your browser.  Javascript code is compled from here:

  https://github.com/malloydata/malloy-composer