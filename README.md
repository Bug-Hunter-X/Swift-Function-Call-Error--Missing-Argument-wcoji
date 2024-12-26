# Swift Function Call Error: Missing Argument

This repository demonstrates a common error in Swift: forgetting to provide all required arguments when calling a function. The compiler will catch this at compile time, preventing runtime crashes.

**Bug:** The `calculateArea` function requires both `width` and `height` arguments. The second call omits the `height` argument, leading to a compile-time error.

**Solution:** Ensure all required arguments are provided when calling a function.  Swift's type safety helps prevent such issues.