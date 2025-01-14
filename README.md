# Implicit Type Coercion with the + Operator in JavaScript

This repository demonstrates a common error in JavaScript related to implicit type coercion when using the addition (+) operator.  Specifically, when one of the operands is `null`, it's implicitly coerced to `0`.

The `bug.js` file showcases the problematic behavior. The `bugSolution.js` file provides a corrected version with explicit null checks.  This is crucial for preventing unexpected behavior and ensuring the reliability of your JavaScript code.