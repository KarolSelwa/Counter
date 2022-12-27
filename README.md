# @lolekxdpl/counters

package with two counters `Counter` and `DecreasingCounter` constructors

## Instalation

```
npm install @lolekxdpl/counters
```

## Usage

To run demo app clone this repo and siply run:

```
npm install
```

```
npm start
```
## API


Every counter gets one argument-selectorof element to be rendered in. Counter should be initialized after creation by calling .init() method


```Javascript

import { Counter, DecreasingCounter } from '@lolekxdpl/counters'

const counter1 = new Counter('.counter-1')
counter1.init()
const counter2 = new DecreasingCounter('.counter-2')
counter2.init()
```