# Your First Android App
A function in programming is a code block that performs a specific task. Functions are defined first—where instructions are set—then called to execute those instructions.

Define vs. Call: Defining a function specifies the task steps, while calling it runs those steps. For example, writing instructions to bake a cake (defining) and following them each time you bake (calling).

Defining a Function: Key parts include:

- Name: Identifies the function for later calls.
- Inputs (Parameters): Optional values that the function may need to perform its task.
- Body: Contains the code instructions to execute the function’s purpose.
In some languages, "declare" and "define" functions might have distinct meanings.

In Kotlin, functions are defined using a specific structure. A function starts with the keyword fun, followed by a name, inputs in parentheses, and the body of instructions within curly braces.

Example of Defining a Function
The basic syntax for a function in Kotlin is:

```
fun functionName(inputs): ReturnType {
    // function body
}
```
For example, the main function in Kotlin:
```
fun main() {
    println("Hello, world!")
}
```
In this example:

Function keyword (fun): Used to start the function.
- Function name: main, which is special in Kotlin as it acts as the entry point.
- Inputs: Empty parentheses, indicating no inputs are required.
- Function body: Contains one statement, println("Hello, world!"), which outputs text.
Naming Conventions
- Use camelCase (e.g., calculateTip, displayErrorMessage).
- Avoid using Kotlin keywords for function names.
Inputs (Parameters)
Inputs are optional and listed in parentheses after the function name. They provide data needed for the function’s task. If there are no inputs, the parentheses remain empty ().

Example Functions
1. Function with Input:
```
fun addOne(number: Int): Int {
    return number + 1
}
```
Purpose: Adds 1 to the input number.
2. Function with Multiple Inputs:
```
fun printFullName(firstName: String, lastName: String) {
    println("$firstName $lastName")
}
```
Purpose: Displays a person’s full name.
3. Function without Inputs:
```
fun displayHello() {
    println("Hello")
}
```
Purpose: Prints "Hello" to the output.
## Calling the println() Function
The println() function in Kotlin outputs text to the console. It requires one input (a message) enclosed in quotation marks, like "Hello, world!". When executed, this message is displayed as output.
