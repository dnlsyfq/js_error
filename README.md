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

// errors 

syntax // semicolons , brackets
runtime // infinity error
logical // math error 
user input // invalid data 

// try ... catch 

```
let totalPrice = 15.99;

try {
    let avgPrice = totalPrice / numItem
    console.log(`USD ${avgPrice}`)
} catch(error){
    console.log(`Error: ${error.message} `)
}

```


// if .. else 

```
let userEmail;
if(!userEmail){
  console.log('Use Email')
}else if(!userEmail.includes('@')){
  console.log('Email must contains @')
}




```
