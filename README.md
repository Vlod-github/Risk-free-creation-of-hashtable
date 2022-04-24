# Risk-free creation of hashtable
## Example
```scala
local hashtable ht = HT_create()
call SaveInteger(ht, 0, 0, 123)
call SaveInteger(ht, 0, 1, 124)
call FlushChildHashtable(ht, 0)
call HT_destroy(ht)
set ht = null
```