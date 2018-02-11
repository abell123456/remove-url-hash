# remove-url-hash

remove url's hash value without reload.

## example

For example,we have a browser url like this:  

`www.alibaba.com/#a=b`  

If we want to remove the hash value and not want to refresh the page,we can do like this:

```javascript
import removeUrlHash from 'remove-url-hash';

removeUrlHash();
```

Then,the url will be:  

`www.alibaba.com`  

and whithout browser refresh!