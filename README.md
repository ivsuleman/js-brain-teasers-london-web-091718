# JS brain teasers

Test your JavaScript knowledge with these brain teasers. Discuss the code with your table and explain what you think will happen before running in console.

1. Given the following **immediately-invoked function expression**...
```javascript
(function(){
  var a = b = "sea";
})();
```
what would happen if you ran:

```javascript
console.log((typeof a !== 'undefined'));
console.log((typeof b !== 'undefined'));
```

2. What would each of the following functions return and why?
```javascript
function foo1()
{
  return {
      bar: "hello"
  };
}

function foo2()
{
  return
  {
      bar: "hello"
  };
}
```

3. What will be the output of each of the following console.logs?
```javascript
console.log(0.1 + 0.2);
console.log(0.1 + 0.2 == 0.3);
```

4. What order will the following numbers log to the console when this IIFE is run?
```javascript
(function() {
    console.log(1); 
    setTimeout(function(){console.log(2)}, 1000); 
    setTimeout(function(){console.log(3)}, 0); 
    console.log(4);
})();
```

## Resources
- [36 Essential JavaScript Interview Questions](https://www.toptal.com/javascript/interview-questions) (Answers located here)
- [IIFE](https://developer.mozilla.org/en-US/docs/Glossary/IIFE)
- [How to Deal with Floating Point Precision in JavaScript](https://stackoverflow.com/questions/1458633/how-to-deal-with-floating-point-number-precision-in-javascript)
- [JavaScript Use Strict](https://www.w3schools.com/js/js_strict.asp)

