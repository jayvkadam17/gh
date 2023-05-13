<!DOCTYPE html>
<html>
<head>
  <title>JavaScript Examples</title>
  <script>
    // Task 1: Hoisting Example - Function "addNumbers"
    addNumbers(3, 4);

    function addNumbers(a, b) {
      console.log("Sum:", a + b);
    }

    // Task 2: Hoisting Example - Function Expression "multiplyNumbers"
    multiplyNumbers(5, 6);

    var multiplyNumbers = function(a, b) {
      console.log("Product:", a * b);
    };

    // Task 3: Variable Hoisting - Using "var" inside a function
    sum(3, 4);

    function sum(a, b) {
      console.log("Result:", result); // Output: undefined
      var result = a + b;
      console.log("Result:", result); // Output: 7
    }

    // Task 4: Variable Hoisting - Using "let" and "var" in block scope
    {
      console.log("x:", x); // Output: undefined
      console.log("y:", y); // Output: ReferenceError: y is not defined

      let x = 5;
      var y = 10;

      console.log("x:", x); // Output: 5
      console.log("y:", y); // Output: 10
    }

    console.log("x:", x); // Output: ReferenceError: x is not defined
    console.log("y:", y); // Output: 10

    // Task 5: Temporal Dead Zone Example - Using "let" inside a block scope
    {
      console.log("x:", x); // Output: ReferenceError: Cannot access 'x' before initialization
      let x = 5;
      console.log("x:", x); // Output: 5
    }

    console.log("x:", x); // Output: ReferenceError: x is not defined
  </script>
</head>
<body>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
  <title>JavaScript Examples</title>
  <script>
    // Task 1: Hoisting Example - Function "addNumbers"
    addNumbers(3, 4);

    function addNumbers(a, b) {
      console.log("Sum:", a + b);
    }

    // Task 2: Hoisting Example - Function Expression "multiplyNumbers"
    multiplyNumbers(5, 6);

    var multiplyNumbers = function(a, b) {
      console.log("Product:", a * b);
    };

    // Task 3: Variable Hoisting - Using "var" inside a function
    sum(3, 4);

    function sum(a, b) {
      console.log("Result:", result); // Output: undefined
      var result = a + b;
      console.log("Result:", result); // Output: 7
    }

    // Task 4: Variable Hoisting - Using "let" and "var" in block scope
    {
      console.log("x:", x); // Output: undefined
      console.log("y:", y); // Output: ReferenceError: y is not defined

      let x = 5;
      var y = 10;

      console.log("x:", x); // Output: 5
      console.log("y:", y); // Output: 10
    }

    console.log("x:", x); // Output: ReferenceError: x is not defined
    console.log("y:", y); // Output: 10

    // Task 5: Temporal Dead Zone Example - Using "let" inside a block scope
    {
      console.log("x:", x); // Output: ReferenceError: Cannot access 'x' before initialization
      let x = 5;
      console.log("x:", x); // Output: 5
    }

    console.log("x:", x); // Output: ReferenceError: x is not defined
  </script>
</head>
<body>
</body>
</html>
