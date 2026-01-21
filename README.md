# C-String-Copy-Using-strcpy
This repository demonstrates how to copy one C-style string into another using the strcpy() function from the &lt;cstring> library in C++. It is a basic example aimed at beginners learning string handling in C++.
# C String Copy Using strcpy()

## 📌 Overview
This project explains how to copy one character array (string) into another using the `strcpy()` function in C++.

## 🧠 Concepts Covered
- C-style strings
- Character arrays
- `strcpy()` function
- `<cstring>` header file

## 💻 Source Code
```cpp
#include<iostream>
#include<cstring>
using namespace std;

int main(){
    char s1[20] = "ranjith";
    char s2[20] = "good morning";

    strcpy(s1, s2);

    cout << s2 << endl;
    return 0;
}
