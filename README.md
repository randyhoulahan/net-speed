---
sidebarDepth: 2
---
# Net Speed

## Description

Estimate the clients network speed.

## Install

```bash
yarn add @houlagins/net-speed

#OR 

npm install @houlagins/net-speed
```
   hgjfhgfgfhj
## API

### default

Returns a String indicating 2g | 3g | 4g | 5g

```js
import getSpeed from '@houlagins/net-speed'

showSpeed()

async function showSpeed(){
  const speed = await getSpeed()

  console.log(speed)
}
```
