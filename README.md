```
$ npm install
$ ./node_modules/.bin/jscs src
Expected token value ":" but = found at src/all.es :
     1 |function a ({ foo = false, bar = null } = {}) {
--------^
     2 |    console.log(bar);
     3 |}
```
