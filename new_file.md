```js
<! -- BY REDUCE METHOD CONVERT AN ARRAY TO OBJECT -->
const data = [{name:'sohan', price:199}, {name:'jagdish', price:150}]
const reduceData =  data.reduce((prev, next) => ({
    ...prev, 
    [next.name]: next
}), {})


<! -- BY REDUCE GET SOME OF ARRAY -->
const arrReduce = [1,2,3,4,5].reduce((prev, next) => (prev + next), 0);

```
