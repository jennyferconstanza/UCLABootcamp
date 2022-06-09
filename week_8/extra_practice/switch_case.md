### If-Statements to Switch-Case

Convert the following set of conditions in the function to a "switch case":

```javascript
// Function def
function checkType(val) {
    if(typeof val == "string") {
        console.log("Val is a string!");
    } else if(typeof val == "number") {
        console.log("Val is a number!");
    } else if(typeof val == "boolean") {
        console.log("Val is a boolean!");
    } else {
        console.log("Val is something else!!!);
    }
}

// To test:
checkType(true);
checkType("true");
checkType(1);
```