# Let

Let is a  variable type that cannot be redeclared for example. Below I have tried to redefine person, which has resulted in a syntax error.

```javascript
let person = "nathan"
//redeclaring person
let person = "pp"
console.log(person)

//output:
//Uncaught SyntaxError: Identifier 'person' has already been declared
```

## When should you use Let?

You should use let when you know that the value you are setting should not change, If the Variable you want is strictly going to be for one specific value, then Let or Const is the variable type you should use since you do not want to redeclare them.



For example I have set my name to John, since I want John to be the fixed value that cannot be changed.

<figure><img src="../../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>
