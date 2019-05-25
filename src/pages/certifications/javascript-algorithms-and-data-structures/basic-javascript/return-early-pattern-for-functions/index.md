---
title: Return Early Pattern for Functions
---
## Return Early Pattern for Functions

Here's a working solution in case you are stuck:

```js
// Setup
function abTest(a, b) {
  // Only change code below this line
  if (a < 0 ||  b < 0 ) {
    return undefined;
  }
  // Only change code above this line

  return Math.round(Math.pow(Math.sqrt(a) + Math.sqrt(b), 2));
}

// Change values below to test your code
abTest(2,2);
```

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
