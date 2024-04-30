## SimplCalc Interpreter

The SimplCalc Interpreter is a Python program designed to interpret and execute scripts written in the SimplCalc language. SimplCalc is a simple scripting language with support for basic prefix arithmetic operations, variable assignment, conditionals, loops, and printing.

### Features

* **Variable Assignment:** Define variables using the `(define <variable> <expression>);` syntax.
* **Arithmetic Expressions:** Perform arithmetic operations such as addition, subtraction, multiplication, and division.
* **Conditionals:** Use if statements `(if <condition> : <statement>);` to execute code conditionally.
* **Loops:** Utilize while loops `(while <condition> : <statement>);` for repetitive tasks.
* **Printing:** Print variable values and expressions using the `(print (<content>));` syntax.

### Getting Started

#### Prerequisites

* Python 3.x installed on your system.

#### Installation

1. Clone the SimplCalc Interpreter repository:

```
git clone https://github.com/ItsSnirLevi/PL_Project-SimplCalc.git
```

2. Navigate to the project directory:

```
cd PL_Project-SimplCalc
```

#### Usage

1. Write your SimplCalc script in a text file, e.g., `script.txt`. There is also an example script (`example_script.txt`) you can try.
2. Run the interpreter with your script:

```
python interpreter.py script.txt
```

3. View the output generated by the interpreter.

### Examples

Here are some examples of SimplCalc scripts you can try:

1. **Simple Arithmetic:**

```
(define x 10);
(define y 20);
(print (+ x y));
```

2. **Conditional Statement:**

```
(define x 10);
(if (< x 15) :
  (print ("x is less than 15"));
);
```

3. **While Loop:**

```
(define x 0);
(while (< x 5) :
  (print (x));
  (define x (+ x 1));
);
```

### Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or create a pull request on GitHub.
