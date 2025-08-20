# C++ Variables and Data Types Exercises

## Descriptive Questions with Short Answers

**1. What is a variable in C++?**  
A variable is a named memory location used to store data.  

**2. Define a variable and explain its purpose in C++.**  
A variable is a container for data; purpose is to store and manipulate values.  

**3. What data type would you use to store an age in C++?**  
```cpp
int age = 25;
```  

**4. What does the int data type store?**  
It stores whole numbers.  
```cpp
int marks = 95;
```  

**5. Explain the difference between float and double data types.**  
- `float` = single precision (7 digits)  
- `double` = double precision (15–16 digits)  

**6. What data type would you use to store a character?**  
```cpp
char grade = 'A';
```  

**7. What is the default value of a bool variable in C++?**  
- Local → undefined (garbage)  
- Global/Static → `false`  

Example:  
```cpp
bool isOn = true, isOff = false;
```  

**8. Declare a variable x of type int and assign it the value of 10.**  
```cpp
int x = 10;
```  

**9. How do you assign one value to multiple variables in C++?**  
```cpp
int a, b, c;
a = b = c = 5;
```  

**10. What is the purpose of using the const keyword in C++?**  
To create a read-only variable.  
```cpp
const float PI = 3.14;
```  

**11. What is the rule for naming variables in C++?**  
- Must start with a letter or underscore  
- Cannot use keywords  
- No spaces/special characters (except `_`)  
