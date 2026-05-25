# Null vs. Undefined  [No COMPLETED]

If you're coming from Python, you might be thinking:

Ah, so is like ! Easy peasy.undefinedNone

Yes. But also... no. One of JavaScript's most cursed features is that it has two values for "nothing":

undefined: It doesn't exist at all. In grug-speak is "very nothing"undefined
null: It (kind of) exists, but it's empty. In grug-speak is "kinda nothing"null
There are some practical differences between the two, the primary one being that is the default value of a variable when it hasn't been given a value yet.undefined

let myName;
console.log(myName); // undefined

To get a value, you have to explicitly assign it:null

let myName = null;
console.log(myName); // null

Confusingly, returns for :typeof"object"null

console.log(typeof null); // object

To be clear, null is its own type according to the ECMAScript specification, but the "object" type report is a historical quirk that can't be easily fixed now.

In most cases, and work the same way, but you'll want to be consistent in how you use them, and know that there are subtle behavioral differences.nullundefined

I personally use almost everywhere I would use in Python or in Go. JavaScript is fairly unique in having two options. I only use in cases where the behavioral difference matters, or I'm relying on external code that forces me to use .undefinedNonenilnullnull

Assignment
Textio has lots of legacy code that checks if specific values are . Just to be safe, the engineering team decided on a standard where variables that aren't declared with a specific value should be set to instead of the default . Fix the code so that each variable holds a value.nullnullundefinednull