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

<a href='https://github.com/freecodecamp/guides/tree/master/src/pages/certifications/javascript-algorithms-and-data-structures/basic-javascript/return-early-pattern-for-functions/index.md' target='_blank' rel='nofollow'>Help our community expand this</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
