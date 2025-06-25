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
