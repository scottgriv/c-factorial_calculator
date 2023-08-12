# Factorial Calculator (C Project)

This simple C project calculates the factorial of a given number. However, due to limitations of the data types used in C, the program cannot accurately calculate factorials for very large numbers (e.g., factorial of 125). This is because the `unsigned long long` data type has a maximum value it can hold.

If you need to accurately calculate the factorial of very large numbers, consider using the GNU Multiple Precision Arithmetic Library (GMP). This library provides arbitrary-precision arithmetic, allowing you to handle large integers that go beyond the capabilities of standard C data types.n.

## Usage
1. Make sure you have a C compiler (e.g., GCC) installed on your system.
2. Compile the code:
```bash
   gcc -o factorial_project main.c
```
3. Run the executable:
```bash
   ./factorial_project
```
4. Enter a number to calculate its factorial.

## License
This project is released under the terms of the **Unlicense**, which allows you to use, modify, and distribute the code as you see fit. The Unlicense removes traditional copyright restrictions, giving you the freedom to use the code in any way you choose.

For more details, see the [LICENSE](LICENSE) file in this repository.

## Credits
**Author:** Scott Grivner <br>
**Email:** scott.grivner@gmail.com <br>
**Website:** [scottgrivner.dev](https://www.scottgriv.dev) <br>
**Reference:** [Main Branch](https://github.com/scottgriv/c-factorial_calculator) <br>