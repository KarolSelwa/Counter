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


Every counter gets two arguments:

-selectorof element to be rendered in.
-start number.

 Counter should be initialized after creation by calling .init() method


```Javascript

import { Counter, DecreasingCounter } from '@lolekxdpl/counters'

const counter1 = new Counter('.counter-1',5)
counter1.init()
const counter2 = new DecreasingCounter('.counter-2',-12)
counter2.init()
```