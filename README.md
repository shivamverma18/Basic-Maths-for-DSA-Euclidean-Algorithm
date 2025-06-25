# Basic-Maths-for-DSA-Euclidean-Algorithm

```bash
1) Count Digit

#include <bits/stdc++.h>
using namespace std;

int count(int n) {
    int cnt = 0;
    while (n > 0) {
        cnt = cnt + 1;
        n = n / 10;
    }
    return cnt;
}

int main() {
    int n;
    cin >> n;
    cout << "Total Digit: " <<count(n) << endl; 
    return 0;
}
```
```bash
7789
Total Digit: 4
```

```bash
2) Reverse a Number
#include <bits/stdc++.h>
using namespace std;

int rev(int n) {
    int revNum = 0;
    while (n > 0) {
        int lastDigit = n % 10;
        n = n/10;
        revNum = (revNum * 10) + lastDigit;
    }
    
}

int main() {
    int n;
    cin >> n;
    cout << "Reverse Number : " <<rev(n) << endl; 
    return 0;
}

```
```bash
Output: 
1234
Reverse Number : 4321

```


# 📘 Basic Maths for DSA – Euclidean Algorithm

This repository contains fundamental C++ programs used frequently in Data Structures and Algorithms (DSA) preparation. These are foundational building blocks for mastering number-based problems.

---

## 📌 Contents

1. [Count Digits in a Number](#-1-count-digits-in-a-number)
2. [Reverse a Number](#-2-reverse-a-number)

---

## 🔢 1. Count Digits in a Number

### ✅ Problem Statement:
Count the number of digits in a given number.

### 📄 Code:
```cpp
#include <bits/stdc++.h>
using namespace std;

int count(int n) {
    int cnt = 0;
    while (n > 0) {
        cnt++;
        n /= 10;
    }
    return cnt;
}

int main() {
    int n;
    cin >> n;
    cout << "Total Digit: " << count(n) << endl;
    return 0;
}

```
```bash
Output: 
7789
Total Digit: 4
```
