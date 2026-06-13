## Lesson 1 - C++ Basics in 1 shot

To start any program, we need a skeleton of the code.

### 1) Including relevant libraries
- `#include <iostream>` - allows input/output
- `#include <math.h>` - allows math functions
- `#include <string>` - allows string operations

### 2) Main function
```cpp
#include <iostream>
int main(){
    std::cout << "Hey Striver!" << '\n';
    return 0;
}
```

we can also use std::endl instead of \n as a newline character

```cpp
#include <iostream>
int main(){
    std::cout << "Hey Striver!" << std::endl;
    return 0;
}
```

but usually people use \n as its faster
As most of the code used std:: we can eliminate is by writing 'using namespace std;'

```cpp
#include <iostream>
using namespace std;

int main(){
    cout << "Hey Striver!" << endl;
    return 0;
}
```

### Taking Inputs

```cpp
#include <iostream>
using namespace std;

int main(){
    int x;
    cin >>x;
    cout<< "Value of x: " << x;
    return 0;
}
```