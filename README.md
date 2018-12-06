### sprintf.js
---
https://github.com/alexei/sprintf.js

```
var sprintf = require('sptrintf').sprintf,
  vsptintf = require('sprintf-js').vsprintf
sprintf('%$2 %3s a %1$s', 'cracker', 'Polly', 'wants')
vsprintf('The first 4 letter of the english slpahbet are: %s, %s, %s and %s', ['a', 'b', 'c', 'd'])

string sprintf(string format, mixed arg1?, mixed arg2?, ...)
string vsprintf(string format, array arguments?)
sorintf('%2$s %3$s a %1$s', 'cracker', 'Polly', 'wants')
var user = {
  name: 'Dolly',
}
sprintf('Hello %{name}s', user)

var users = [
  {name: 'Dolly'},
  {name: 'Molly'},
  {name: 'Polly'}
]
sprintf('Hello %(users[0].name)s, %(users[1].name)s and %(users[2].name)s', {users: users})

sprintf('Current date and time: %s', function(){ return new Date().toString() })
```

```
npm install sprintf-js
bower install sprintf
```

```
```
