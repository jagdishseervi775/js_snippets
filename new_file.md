```js
const data = [{name:'sohan', price:199}, {name:'jagdish', price:150}]
const reduceData =  data.reduce((prev, next) => ({
    ...prev, 
    [next.name]: next
}), {})

```
