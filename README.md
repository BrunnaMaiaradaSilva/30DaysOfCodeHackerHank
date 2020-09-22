# 30DaysOfCodeHackerHank

### 30 Days of Code!

## Day 0 of Code: Print Hello World!


```
function processData(inputString) {
    // This line of code prints the first line of output
    process.stdout.write("Hello, World." + "\n");
     // Write the second line of output that prints the contents of 'inputString' here.
     process.stdout.write(inputString);
}


process.stdin.resume();
process.stdin.setEncoding("ascii");
_input = "";
process.stdin.on("data", function (input) {
    _input += input;
});

process.stdin.on("end", function () {
   processData(_input);
});
```
