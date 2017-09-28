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
