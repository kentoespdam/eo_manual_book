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
     - if has upload file regex some replacing &quote; to \\\\"
6. _get_response($print = false)
7. _print($response)
8. _rpc($cdata)

---

