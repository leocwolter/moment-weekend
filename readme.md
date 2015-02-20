moment-weekend
==============

Using the moment.js to work out the number of days passed NOT including the weekend.


Installing
----------

```
npm install moment-weekend
```

Example
-------

```
var moment = require('moment');
var weekend = require('moment-weekend');

var start = moment("2015-02-12", "YYYY-MM-DD")
var end = moment("2015-02-17", "YYYY-MM-DD")
var result = weekend.diff(start, end); 

// result = 3
```