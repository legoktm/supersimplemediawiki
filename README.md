supersimplemediawiki
===================
By [en:User:Legoktm](http://enwp.org/User:Legoktm). Released under the terms of the MIT License.
* Only requirement is [requests](http://python-requests.org/)
* Supports any wiki with an ```api.php```

Usage
-------

```
import mw
enwp = mw.Wiki('http://en.wikipedia.org/w/api.php')
enwp.login('username','password')
enwp.request({'action':'query'}) #etc...
```
