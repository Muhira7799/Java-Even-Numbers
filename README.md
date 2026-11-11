# Java Even Numbers Example

A small Java program that prints all the even numbers from 2 up to 68 on one line.

## What It Demonstrates

```java
for (int i = 2; i < 70; i += 2) {
    System.out.print(i + " ");
}
System.out.println();
```

- A `for` loop that starts at `2`
- Stepping by 2 with `i += 2`, so only even numbers are visited
- `print` (no new line) instead of `println`, so everything stays on one line
- A final `println()` to move the cursor to the next line

## How It Works

1. `i` starts at `2`.
2. While `i < 70`, the loop prints `i` followed by a space.
3. After each pass, `i` increases by 2.
4. The last value printed is `68`, because the next value, `70`, fails the condition `i < 70`.

## Output

```
2 4 6 8 10 12 14 16 18 20 22 24 26 28 30 32 34 36 38 40 42 44 46 48 50 52 54 56 58 60 62 64 66 68
```

## Requirements

- Java Development Kit (JDK) 8 or higher

## Getting Started

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
javac Q_2.java
java Q_2
```

## Try It Yourself

- Print the odd numbers: start at `1`
- Include 70 by changing the condition to `i <= 70`
- Count down from 68 to 2 with `i -= 2`

## Project Structure

```
.
├── Q_2.java
└── README.md
```

## Next Steps

- Add up all the even numbers
- Let the user choose the upper limit with `Scanner`
- Print only the even numbers that are divisible by 4
