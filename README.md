# Handy-TimeAgo

A very simple, handy & useful TimeAgo API which can be used very easily!!


# Usage

```javascript
import HandyTimeAgo from 'handy-timeago'
HandyTimeAgo(time:String||Number):String
```

# Examples

```javascript
import HandyTimeAgo from 'handy-timeago'
let time = new Date().getTime()-10000
console.log(HandyTimeAgo(time))
>> "10 seconds ago"
```

**Thanks for reading!!**