# timeunit

## install

```
npm i @yehonadav/timeunit
```

stop using syntax ```const wait = 24 * 60 * 60 * 1000``` to represent time units.  
use a time unit instead: 

## usage

```typescript
import {seconds} from "@yehonadav/timeunit"

function sleep(milliseconds) {
  return new Promise(resolve => setTimeout(resolve, milliseconds))
    .then(() => {
      console.log(`waited ${milliseconds/second} seconds`)
    })
}

sleep(60 * seconds)
```

enjoy =)  
