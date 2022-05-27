# GET_JSON_VALUE
SQL Server 2014 JSON_VALUE alternative

Example Usage of Path: statu[0].column, statu.column, statu.column.subcolumn, statu etc.

GET_JSON_VALUE('{"foo":"baz", "lorem":{"ipsum":"dolar", "sit":"amet"}}', lorem.ipsum)
