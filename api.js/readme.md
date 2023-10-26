# Explanation api.js

## Descriptions

> api.js file is library for frontend to generating view based on user role and action

## api.js Structure

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
}
```

#### Explanation

- url : server url
- type : access server type
- actions : list of class & method can be accessed from frontend
  - classname : class name, contains a list of accessible methods
    - name : method name
    - len : number of parameters that must be passed from the frontend
- namespace : namespace
