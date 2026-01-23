# Trainings for quantitative interviews

## Pre-requisites
It is recommended to use Python 3.13 and a virtual environment.

### 1. Create a virtual environment
```bash
python3 -m venv venv
source venv/bin/activate
```

### 2. Install dependencies
```bash
python -m pip install -r requirements.txt
```

## Flash cards
### Useful formulas

Number of trailing zeros in $n!$:
```math
= \sum_{i=1}^{N} \frac{n!}{5^i}
\qquad\n
\text{Where } 5^i \leq n
```

Series summation of the first $n$ numbers (Gauss):
```math
\sum_{n=1}^{N}n = \frac{N(N+1)}{2}
```

Series summation of the first $n$ odd numbers:
```math
1+3+...+(2n-1)=n^2
```

Series summation of the first $n^2$ numbers:
```math
\sum_{n=1}^{N}n^2 = \frac{N^3}{3}+\frac{N^2}{2}+N
```

**References...**
Zhou, X., & Jiu, B. (2008). A practical guide to quantitative finance interviews.
