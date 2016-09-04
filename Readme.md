node-snowflake
==============

node-snowflake is a node.js clone for [twitter snowflake](https://github.com/twitter/snowflake).

###how to use
```
var snowflake = require('node-snowflake').Snowflake;

snowflake.init({worker_id : 1, data_center_id : 1, sequence : 0});

var id = snowflake.nextId();

console.log(id);
```