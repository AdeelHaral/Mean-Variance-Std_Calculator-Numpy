# **Matrix Calculator**

This project is a simple Python program that takes a list of nine numbers as input, reshapes it into a 3x3 matrix, and calculates several statistical properties (mean, variance, standard deviation, maximum, minimum, and sum) for the matrix across rows, columns, and the entire matrix.

---

## **Features**
- Accepts a list of nine numbers and reshapes it into a 3x3 matrix.
- Computes:
  - Mean
  - Variance
  - Standard Deviation
  - Maximum
  - Minimum
  - Sum
- Returns results in a structured dictionary format.

---

## **Technologies Used**
- Python 3
- NumPy (for efficient numerical computations)

---

---

## **Input**
- A list of exactly **nine numbers** (e.g., `[0, 1, 2, 3, 4, 5, 6, 7, 8]`).

### **Example Input**
```python
[0, 1, 2, 3, 4, 5, 6, 7, 8]
```

## **Output**
The program outputs a dictionary with the following keys:
- `mean`
- `variance`
- `standard deviation`
- `max`
- `min`
- `sum`

Each key contains a list of results for:
1. Columns
2. Rows
3. The entire matrix

### **Example Output**
```python
{
    'mean': [[3.0, 4.0, 5.0], [1.0, 4.0, 7.0], 4.0],
    'variance': [[6.0, 6.0, 6.0], [0.6666666666666666, 0.6666666666666666, 0.6666666666666666], 6.666666666666667],
    'standard deviation': [[2.449489742783178, 2.449489742783178, 2.449489742783178], [0.816496580927726, 0.816496580927726, 0.816496580927726], 2.581988897471611],
    'max': [[6, 7, 8], [2, 5, 8], 8],
    'min': [[0, 1, 2], [0, 3, 6], 0],
    'sum': [[9, 12, 15], [3, 12, 21], 36]
}
```

---

## **Error Handling**
- If the input list does not contain exactly nine numbers, the program raises a `ValueError`:
  ```python
  ValueError: List must contain nine numbers.
  ```

---

## **Contributing**
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`feature/your-feature-name`).
3. Commit your changes.
4. Push to the branch.
5. Create a pull request.

---

## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---



---

Let me know if you want help customizing this further! 🚀
