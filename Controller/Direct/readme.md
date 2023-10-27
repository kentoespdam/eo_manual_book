# Direct Controller

## Explanation

> this is the main controller of server where all of request requesting data to here

### function list

---

1. index()
2. api()
   - generating cache
   - print api as javascript
3. router()
   - getting resource from session
   - parsing request from client
4. _parse_request()
   - validating input value from post request
5. _dispatch()
   - generating response based request data
     - if is array data, explode and run one by one. else just run it
     - if has upload file replace &quote; to \\\\"
6. _get_response($print = false)
   - returning response
      - check if has response created, if no response created run _dispatch()
      - check $print status, if True execute _print()
7. _print($response)
   - echo'ing response
      - if not form set header to javascript
8. _rpc($cdata)
   - build response based data request
      - check exist classes
      - execute class method based request method data

---
