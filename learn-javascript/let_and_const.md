# let and const
The var keyword is the "old" way to declare variables in JavaScript. These days, you should use let and const instead. The let keyword is for variables that can be reassigned, while const is for variables that can't.

```javascript
let username = "dengar_the_bh";
username = "boba_fett";

const smsSendingLimit = 1000;
```

Use const for values that never change, and let for values that do.

> [!CAUTION]
> The var keyword is function-scoped instead of block-scoped, meaning when it's used inside an if block the variable leaks out, while let and const don't.
> 
> You'll encounter legacy code that uses var, so you need to know about it, but migrate it to let or const when you can.
> 

## Assignment
The code as-is sends two birthday messages (oops) instead of a welcome message and a birthday message!

1. Run the code to see the bug (but don't submit yet!).
2. Fix the bug by changing the var keywords to let or const as appropriate.

Once fixed, submit your code.

---

---

## Initial Code

```javascript

var messageText = "Welcome to Textio!";
var isBirthday = true;

if (isBirthday) {
  var messageText = "Happy Birthday!";

  console.log("Sending birthday message...");
  console.log("Message:", messageText);
}

// don't touch below this line

console.log("Sending welcome message...");
console.log("Message:", messageText);
```

## Solution

Let me run the buggy code first to see the issue.The bug is confirmed — both messages print "Happy Birthday!" because `var` is **function-scoped** (not block-scoped). The `var messageText` inside the `if` block doesn't create a new variable — it overwrites the outer one, so the welcome message is lost.

**The fix:** use `const` for the outer `messageText` (it never changes) and `let` for the inner one (block-scoped, so it stays inside the `if` block).Each message now sends correctly. Here's the fixed code to submit:

```js
const messageText = "Welcome to Textio!";
const isBirthday = true;
if (isBirthday) {
  let messageText = "Happy Birthday!";
  console.log("Sending birthday message...");
  console.log("Message:", messageText);
}
// don't touch below this line
console.log("Sending welcome message...");
console.log("Message:", messageText);
```

**What changed and why:**
- `var messageText` → `const messageText` (outer): it's never reassigned, and `const` is block-scoped, so it's protected from being overwritten.
- `var messageText` → `let messageText` (inner): `let` is block-scoped, so this variable only exists inside the `if` block and doesn't clobber the outer one.
- `var isBirthday` → `const isBirthday`: it's never reassigned, so `const` is the right choice.
