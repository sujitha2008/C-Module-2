# C-Module-2

**2a) Write a c program to find the sum of odd digits using while loop.**

**AIM:**

To write a C program to find the sum of odd digits using while loop.

**ALGORITHM:**

1. Read the value of `n` and initialize `i = 1`, `sum = 0`.

2. While `i ≤ n`, check if `i` is odd; if yes, add it to `sum`, then increment `i`.

3. Print the value of `sum` and stop.


**PROGRAM:**
```
#include <stdio.h>

int main()
{
    int n, i = 1, sum = 0;

   
    scanf("%d", &n);

    while(i <= n)
    {
        if(i % 2 != 0)
        {
            sum = sum + i;
        }
        i++;
    }

    printf("%d", sum);

    return 0;
}
```

**OUTPUT:**

<img width="866" height="293" alt="Screenshot 2026-03-24 140614" src="https://github.com/user-attachments/assets/e67fa868-fbd8-4a97-b8c3-3501e33343c6" />

**RESULT:**

Thus, the program is verified successfully.
