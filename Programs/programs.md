# Calculate the area of triagle using Heron's formula

- Enter length of three sides of a triagle.
- Find value of s using - `S = (a + b + c) / 2`
- Find area using - `area = sqrt(s * (s-a) * (s-b) * (s-c))`

```c
#include <stdio.h>
#include <math.h>

void main() {
  float a, b, c;

  scanf("%f", &a);
  scanf("%f", &b);
  scanf("%f", &c);

  float s = (a + b + c) / 2;

  float area = sqrt(s * (s-a) * (s-b) * (s-c));
  printf("%f\n",area);
}
```

- Note: Compile <math.h> using -lm as math.h must be linked in when building the executable.

```
Output:
12 16 20
96.000000
```

# Calculate distance between two points

```c

```
