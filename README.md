# probability.js

```js
const items = [ 
                { 
                    item: false,
                    percent: 10
                },
                { 
                    item: null,
                    percent: 40
                },
                { 
                    item: true,
                    percent: 50
                }
            ]

const probability = new Probability(  ...items )

console.log( probability.random() )
console.log( probability.min() )
console.log( probability.max() )
console.log( probability.get(0) )
```