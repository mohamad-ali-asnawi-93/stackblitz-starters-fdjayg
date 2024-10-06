# Double function  


  ## Steps
  1. Let's create the `double` function:
  ```javascript
  function double(number) {
    const result = number * 2;
    return result;
}
  ```
  2. To run the function and store what is being returned in the `double` function to the `total` variable:
  ```javascript
  const total = double(3);
  ```
  3. To show it on console, we need to `console.log` the `total`:
  ```javascript
  console.log(total);
  ```
  4. Your code should look like this:
  ```javascript
  function double(number) {
    const result = number * 2;
   return result;
}

const total = double(3);
console.log(total);

  ```

 Output:
 
 ```
 6
 ```


<details>
<summary>Full code</summary>
  
```js
function double(number) {
  const result = number * 2;
  return result;
}

const total = double(3);
console.log(total);

```
</details>