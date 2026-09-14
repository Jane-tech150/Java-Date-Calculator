# Java-Date-Calculator
A simple Java program that takes a day number, year, and number of days, then calculates the corresponding date and the date after n days.

## What this program does

The program takes three inputs:

* **Day number** – the day of the year (1–365, or 1–366 for a leap year)
* **Year** – the year
* **n** – the number of days to add (1–100)

It then:

1. Checks whether the entered day number is valid.
2. Checks whether the year is a leap year.
3. Converts the day number into a proper date.
4. Calculates and displays the date after `n` days.
5. Handles the change of month, year, and leap years.

## Example

### Input

```text
Enter day number
60
Enter year
2024
Enter n
10
```

### Output

```text
The date: 29 February, 2024
The date after 10 days: 10 March, 2024
```

## Concepts used

This program uses some basic Java concepts:

* Methods
* `if-else` conditions
* `while` loops
* Arrays
* `String` arrays
* Boolean variables
* `Scanner` for input
* Leap year calculation
* Basic date calculation

## How to run

Make sure Java is installed on your computer.

Compile the program:

```bash
javac date3.java
```

Run it:

```bash
java date3
```

## Notes

The program accepts:

* Day numbers from **1–365** in a normal year
* Day numbers from **1–366** in a leap year
* `n` values from **1–100**

The program also handles moving into the next year if adding `n` days crosses December 31.

