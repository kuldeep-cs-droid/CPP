
# C++ Basic Programs Collection

## 1. Declare an integer and print it
```cpp
#include <iostream>
using namespace std;

int main() {
    int num = 10;
    cout << "The value of num is: " << num;
    return 0;
}
```

---

## 2. Perimeter of a rectangle
```cpp
#include <iostream>
using namespace std;

int main() {
    int length = 10, width = 5;
    int perimeter = 2 * (length + width);
    cout << "Perimeter of rectangle: " << perimeter;
    return 0;
}
```

---

## 3. Constant variable change
```cpp
#include <iostream>
using namespace std;

int main() {
    const int x = 5;
    // x = 10;  ❌  Error: cannot change constant variable
    cout << "Constant value: " << x;
    return 0;
}
```

---

## 4. String variable
```cpp
#include <iostream>
using namespace std;

int main() {
    string name = "Kuldeep Kumar";
    cout << "My name is: " << name;
    return 0;
}
```

---

## 5. Total fee calculation
```cpp
#include <iostream>
using namespace std;

int main() {
    double tuition = 5000.75, hostel = 1000.50, books = 300.20;
    double total = tuition + hostel + books;
    cout << "Total fee: " << total;
    return 0;
}
```

---

## 6. Area of triangle
```cpp
#include <iostream>
using namespace std;

int main() {
    double base = 10, height = 5;
    double area = 0.5 * base * height;
    cout << "Area of triangle: " << area;
    return 0;
}
```

---

## 7. Float with 2 decimal places
```cpp
#include <iostream>
#include <iomanip>
using namespace std;

int main() {
    float x = 12.3456;
    cout << fixed << setprecision(2) << "Value of x: " << x;
    return 0;
}
```

---

## 8. Difference char vs string
```cpp
#include <iostream>
using namespace std;

int main() {
    char c = 'A';       // single character
    string s = "Hello"; // collection of characters

    cout << "Char: " << c << endl;
    cout << "String: " << s;
    return 0;
}
```

---

## 9. Sum of 3 integers
```cpp
#include <iostream>
using namespace std;

int main() {
    int x = 5, y = 10, z = 20;
    cout << "Sum = " << (x + y + z);
    return 0;
}
```

---

## 10. Area & circumference of circle
```cpp
#include <iostream>
using namespace std;

int main() {
    int radius = 7;
    const double PI = 3.14159;
    double area = PI * radius * radius;
    double circumference = 2 * PI * radius;

    cout << "Area: " << area << endl;
    cout << "Circumference: " << circumference;
    return 0;
}
```

---

## 11. Sum of two user inputs
```cpp
#include <iostream>
using namespace std;

int main() {
    int a, b;
    cout << "Enter two numbers: ";
    cin >> a >> b;
    cout << "Sum = " << a + b;
    return 0;
}
```

---

## 12. Average of 3 numbers
```cpp
#include <iostream>
using namespace std;

int main() {
    double a, b, c;
    cout << "Enter 3 numbers: ";
    cin >> a >> b >> c;
    double avg = (a + b + c) / 3;
    cout << "Average = " << avg;
    return 0;
}
```

---

## 13. Volume of cylinder
```cpp
#include <iostream>
using namespace std;

int main() {
    int radius = 5, height = 10;
    const double PI = 3.14159;
    double volume = PI * radius * radius * height;
    cout << "Volume of cylinder: " << volume;
    return 0;
}
```

---

## 14. Area of circle with const PI
```cpp
#include <iostream>
using namespace std;

int main() {
    const double PI = 3.14159;
    double radius;
    cout << "Enter radius: ";
    cin >> radius;
    double area = PI * radius * radius;
    cout << "Area of circle: " << area;
    return 0;
}
```

---

## 15. Simple Interest
```cpp
#include <iostream>
using namespace std;

int main() {
    double P = 1000, R = 5, T = 3;
    double SI = (P * R * T) / 100;
    cout << "Simple Interest: " << SI;
    return 0;
}
```

---

## 16. Fahrenheit to Celsius
```cpp
#include <iostream>
using namespace std;

int main() {
    double F;
    cout << "Enter temperature in Fahrenheit: ";
    cin >> F;
    double C = (F - 32) * 5 / 9;
    cout << "Celsius: " << C;
    return 0;
}
```

---

## 17. Areas of rectangle, square, triangle
```cpp
#include <iostream>
using namespace std;

int main() {
    int length = 10, width = 5, side = 4, base = 6, height = 3;
    cout << "Rectangle Area: " << length * width << endl;
    cout << "Square Area: " << side * side << endl;
    cout << "Triangle Area: " << 0.5 * base * height;
    return 0;
}
```

---

## 18. ASCII value of a char
```cpp
#include <iostream>
using namespace std;

int main() {
    char ch;
    cout << "Enter a character: ";
    cin >> ch;
    cout << "ASCII value of " << ch << " is " << int(ch);
    return 0;
}
```

---

## 19. Factorial of a number
```cpp
#include <iostream>
using namespace std;

int main() {
    int n, fact = 1;
    cout << "Enter a number: ";
    cin >> n;
    for (int i = 1; i <= n; i++) {
        fact *= i;
    }
    cout << "Factorial = " << fact;
    return 0;
}
```

---

## 20. Student info
```cpp
#include <iostream>
using namespace std;

int main() {
    int id = 101, age = 20;
    char grade = 'A';
    double fees = 5000.50;

    cout << "ID: " << id << endl;
    cout << "Age: " << age << endl;
    cout << "Grade: " << grade << endl;
    cout << "Fees: " << fees;
    return 0;
}
```

---

## 21. Total cost with tax
```cpp
#include <iostream>
using namespace std;

int main() {
    double cost = 50.75;
    double taxRate = 8.5; // percent
    double total = cost + (cost * taxRate / 100);
    cout << "Total cost = " << total;
    return 0;
}
```
