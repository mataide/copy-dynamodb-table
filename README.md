Safe Copy Dynamodb Table
===================

This module will allow you to copy data from one table to another using very simple API


## Installation

    $ npm i copy-dynamodb-table

## Usage :

```js
const copyDynamodbTable = require('copy-dynamodb-table').copyDynamodbTable;
copyDynamodbTable({
  firstTableName : '<source table name>',
  secondTableName :  '<destination table name>',
  },
  function(err,results){
    if(err) throw err;
    console.log(` √√`);
})
```
## To do :

- Support cross zone copying
- Support explicit AWS config for each table source & destination

## Contributors :

- Ezzat [@enGMzizo](https://twitter.com/enGMzizo)

## License :

MIT
