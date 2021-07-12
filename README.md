# CodeCademy Store project

### The first step towards completing the cart feature will be to define the actions that can change the state.cart slice, and to handle them in the reducer. Open up cartSlice.js where you will find the addItem() action creator as well as the reducer cartReducer() which can already handle a 'cart/addItem' action. In addition to adding items to the cart, the user should be able to modify the quantity of each item in their cart. First, you will need to create an action creator for this kind of action object.

Below the addItem() function:

##### Note: cartSlice.js,
1a. Declare a new function called changeItemQuantity
```javascript
const changeItemQuantity = () => {

}
```
1b. It should have two parameters: name (a string) and newQuantity (a number)
```javascript
const changeItemQuantity = (name, newQuantity) => {

}
```
1c. It should return an object with two properties: type and payload
```javascript
const changeItemQuantity = (name, newQuantity) => {
  return {
    type: 'cart/changeItemQuantity',
    payload: 'I DONT KNOW WHAT TO PUT HERE'
  }
}
```
1d. The payload should be an object with a .name and .newQuantity property.
```javascript
const changeItemQuantity = (name, newQuantity) => {
  return {
    type: 'cart/changeItemQuantity',
    payload: { name, newQuantity }
  }
}
```
1e. Export this function.
```javascript
export const changeItemQuantity = (name, newQuantity) => {
  return {
    type: 'cart/changeItemQuantity',
    payload: { name, newQuantity }
  }
};
```

```javascript
// Example cart state
cart = {
  'Hat': { price: 15.99, quantity: 0 },
  'T-Shirt': { price: 15.99, quantity: 2 },
  'Hoodie': { price: 18.99, quantity: 1 },
},
```

### Great! Now that you know what changeItemQuantity() actions will look like, you can handle them in the cartReducer(). A case for this action type has already been started for you. It first pulls out the name and newQuantity from the payload and grabs the itemToUpdate from the cart.

The first step is to update this item — but you must do it immutably! Below the variable itemToUpdate…

##### cartSlice.js
2a. Declare a new variable called updatedItem and assign to it a new object.
```javascript
const updatedItem = {};
```

2b. Copy the contents of itemToUpdate into updatedItem but set the quantity property to the value of newQuantity.

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

```javascript

```

