# json2xlsx-export
_Lightweight in browser `.xlsx` exporter._

### How it use

```sh
import json2xlsx-export from 'json2xlsx-export';

const config = {
  filename: 'AwesomeFile',
  sheets: [
    {
      name: 'Sheet1',
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
    },
    {
      name: 'Sheet1',
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
  ]
};

json2xlsx-export(config);
```
