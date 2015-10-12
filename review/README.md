Re Scrum, don't worry too much. It can get very complicated, but most places implement it fairly loosely. At EDA, you'll find it easy to understand and use.

Nice work on the colors. Did you figure out what the `a` in `hsla` or `rgba` stands for and what it's used for?

Thank you for staying pretty close to an 80-character line length. You're the first person I've seen get this right so far. One thing that you should do, though, is that anytime your content spans more than one line, indent and put it on it's own line(s). So this:

```html
<p>The HTML &gt;aside&gt; element represents a section of the page with
content connected tangentially to the rest, which could be
considered separate from that content. These sections are often
represented as sidebars or inserts. They often contain the
definitions on the sidebars, such as definitions from the glossary;
there may also be other types of information, such as related
advertisements; the biography of the author; web applications;
profile information or related links on the blog.</p>
```

Becomes this:

```html
<p>
  The HTML &gt;aside&gt; element represents a section of the page with
  content connected tangentially to the rest, which could be
  considered separate from that content. These sections are often
  represented as sidebars or inserts. They often contain the
  definitions on the sidebars, such as definitions from the glossary;
  there may also be other types of information, such as related
  advertisements; the biography of the author; web applications;
  profile information or related links on the blog.
</p>
```

That makes it much easier to read. Lovely HTML otherwise!

Glad you liked the pair programming. Be sure to trade places occasionally so you get to be both driver and navigator over time.

Nice work on usability and accessibility. I hope the importance of these issues is becoming clear to you. Yes, those numbers are a bit shocking! But true.

On the JavaScript, nice work! But let's change the style a bit. We're using the [standard.js](http://standardjs.com/rules.html#javascript-standard-style) style guide. We'll want spaces around the operators and before the `{`. Also, let's use blank lines (just one) between blocks of code for clarity. And finally, note that your `isOdd` function can be made much simpler. Also, make sure you use `===` not `==` (see the standard above).

So this:

```js
function avg (p1, p2) {
 return (p1+p2)/2
}
function avgOfThree (p1, p2, p3) {
  return (p1+p2+p3)/3
}
function isOdd (num) {
  if(num % 2  == 0){
    return 0;
  }
  else{
    return 1;
  }
}
```

Becomes this:

```js
function avg (p1, p2) {
 return (p1 + p2) / 2
}

function avgOfThree (p1, p2, p3) {
  return (p1 + p2 + p3) / 3
}

function isOdd (num) {
  return num % 2  === 0
}
```

Excellent work overall! Keep it up.
