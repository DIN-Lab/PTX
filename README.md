This is a utility code for PTX authorization.

# Usage
```python
import ptx

app_id = 'FFFFFFFF-FFFF-FFFF-FFFF-FFFFFFFFFFFF' # replace this
app_key = 'FFFFFFFF-FFFF-FFFF-FFFF-FFFFFFFFFFFF' # replace this

dt_str = ptx.getDatetimeString()
signature = ptx.getAuthorization(dt_str, app_id, app_key)
```
