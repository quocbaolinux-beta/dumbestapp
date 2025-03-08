# dumbestapp
Yes, it is.
The most basic application that you have to get used to when studying Tech.
```c
//C
#include <stdio.h>
#include <conio.h>
#include <math.h>
int main()
{
    char characters[1000];
    printf("Enter a string (<=1000 characters): ");
    scanf("%s", characters);
    printf("You just entered a string: %s.", characters);
    return 0;
}
```
```cpp
//C++
#include <bits/stdc++.h>
#define int long long
using namespace std;
string n;
int32_t main()
{
    ios_base::sync_with_stdio(false);
    cin.tie(NULL); cout.tie(NULL);
    cin >> n;
    cout << "\nYou pressed the number/letter/string " << n << "\n";
    return 0;
}

```
