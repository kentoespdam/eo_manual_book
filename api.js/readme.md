# Penjelasan api.js

## Deskripsi

> file api.js merupakan dasar bagi frontend untuk menggenerate view sesuai action dan role user login

## Struktur api.js

### Extension Service name

`Ext.ns('CI');`

### Extension API Description

`CI.APIDesc=`

```json
{
    "url": "http://host/server/direct",
    "type": "remote",
    "actions":{
        "classname":[{
            "name": "validate",
            "len": 0
        }]
    },
    "namespace":"CI"
};
```

#### penjelasan

- url : server url
- type : access server type
- actions : list of class & method can be accessed from frontend
  - classname : class name, contains a list of accessible methods
    - name : method name
    - len : number of parameters that must be passed from the frontend
- namespace : namespace
