# Basic-Maths-for-DSA-Euclidean-Algorithm

```bash

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
