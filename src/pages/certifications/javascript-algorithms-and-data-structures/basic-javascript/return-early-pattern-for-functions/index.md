---
title: Return Early Pattern for Functions
---
## Return Early Pattern for Functions

Here is a solution：

```js
function abTest(a, b) {
  // Only change code below this line
  var c; 
  if(a<0||b<0){
    return c;
  }
  
  // Only change code above this line

  return Math.round(Math.pow(Math.sqrt(a) + Math.sqrt(b), 2));
  ```
}
