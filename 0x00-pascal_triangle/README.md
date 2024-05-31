# 0x00. Pascal's Triangle

Welcome to the 0x00-pascal_triangle project! In this project, you will learn about Pascal's Triangle, a triangular array of the binomial coefficients. Pascal's Triangle is a fundamental concept in mathematics and has applications in algebra, probability, and combinatorics.

## Table of Contents

- [Introduction](#introduction)
- [Learning Objectives](#learning-objectives)
- [Requirements](#requirements)
- [Tasks](#tasks)
- [Usage](#usage)
- [Resources](#resources)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Pascal's Triangle is a triangular array where each entry is the sum of the two entries directly above it. The triangle starts with a 1 at the top, and each row represents the coefficients of the binomial expansion.

Here's an example of the first few rows of Pascal's Triangle:

```
       1
      1 1
     1 2 1
    1 3 3 1
   1 4 6 4 1
```

## Learning Objectives

By the end of this project, you should be able to:

- Understand the concept of Pascal's Triangle.
- Implement a function that generates Pascal's Triangle.
- Apply Pascal's Triangle in solving mathematical problems.

## Requirements

- Python 3.x
- A code editor (e.g., Visual Studio Code, Sublime Text)

## Tasks

### Task 0: Pascal's Triangle

#### Description

Write a function `def pascal_triangle(n):` that returns a list of lists of integers representing the Pascal’s triangle of `n`:

- Returns an empty list if `n <= 0`
- You can assume `n` will be always an integer

#### Example

```python
>>> pascal_triangle(5)
[
 [1],
 [1, 1],
 [1, 2, 1],
 [1, 3, 3, 1],
 [1, 4, 6, 4, 1]
]
```

### Implementation

Create a file named `0-pascal_triangle.py` and implement the `pascal_triangle` function. Here's a brief outline of how you can approach the problem:

1. **Initialize the Triangle**: Start with an empty list to hold the rows of the triangle.
2. **Generate Rows**: Use a loop to generate each row of the triangle. Each row can be constructed based on the previous row.
3. **Handle Edge Cases**: Ensure your function handles edge cases, such as when `n` is 0 or negative.

## Usage

To test your implementation, you can create a test file named `test_pascal_triangle.py`:

```python
from 0-pascal_triangle import pascal_triangle

def test_pascal_triangle():
    print(pascal_triangle(5))
    print(pascal_triangle(0))
    print(pascal_triangle(1))

if __name__ == "__main__":
    test_pascal_triangle()
```

Run the test file to see the output of your function:

```sh
python3 test_pascal_triangle.py
```

## Resources

Here are some additional resources to help you understand and implement Pascal's Triangle:

- [Pascal's Triangle on Wikipedia](https://en.wikipedia.org/wiki/Pascal%27s_triangle)
- [Math is Fun: Pascal's Triangle](https://www.mathsisfun.com/pascals-triangle.html)
- [Khan Academy: Binomial Theorem](https://www.khanacademy.org/math/algebra2/polynomial-functions/binomial-theorem/v/binomial-theorem)

## Contributing

We welcome contributions to improve this project! If you have any suggestions or improvements, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](../LICENSE) file for details.

Happy coding! 🚀

---

If you have any questions or need further assistance, feel free to reach out to the community or the repository maintainers.