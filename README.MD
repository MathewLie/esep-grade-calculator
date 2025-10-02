# ESEP Grade Calculator

This library is a simple utility to calculate your grades. Make sure to install go on your device.

## File Summary
There are **three main files** in this project besides the README.md:
- **go.mod:** a configuration file that manages the project’s versions and dependencies. This is all through Go’s modules system.
- **grade_calculator.go:** file that establishes a struct with variables and methods to insert grades, get weighted averages, and provide a letter grade.
- **grade_calculator_test.go:** file that uses Go’s testing package to run unit tests for the grading scale and system.

For more information on Go and documentation go to this link: https://go.dev/ 

For information on utilizing Go in practice go to this link: https://www.geeksforgeeks.org/go-language/go/ 

## This project's runtime requirements:
Golang 1.24+

## Run unit tests:

The file grade_calculator_test.go contains the unit tests created for this calculator. The tests are used to see what letter grade is outputted based on the grade types. There’s an Expected Grade and Returned Grade, and the tests aim to see if they are the same after running calculations.

To run these unit tests, enter the terminal and run these commands:

```
cd grade_calculator/
go test ./...
```

## Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```