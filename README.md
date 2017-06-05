# json2xlsx-export
_Lightweight in browser `.xlsx` exporter._

### How it use

```sh
import json2xls-export from 'json2xls-export';

const config = {
  filename: 'AwesomeFile',
  sheet: {
    data: [
      [{
        value: 'Line1',
        type: 'string'
      },{
        value: 'Line2',
        type: 'string'
      }, {
        value: 1000,
        type: 'number'
      }]
    ]
  }
};

json2xls-export(config);
```
