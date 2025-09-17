### Error Handling

```
let totalPrice = 40;

try {
  let avgPrice = totalPrice / numItems;
  console.log("Average Price per Item: $", avgPrice);
} catch ( error ){
  console.log(`Error : ${error.message}`)
}

```
