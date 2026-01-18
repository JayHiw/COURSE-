# COURSE-
Here to share about everything about the course 

## 📘 Courses & Learning Focus

This repository also reflects my academic and self-learning journey across core computer science subjects, with a strong emphasis on fundamentals, problem-solving, and practical implementation.

### 🐍 Python Programming
- Core Python syntax and concepts  
- Data types, control flow, functions, and modules  
- File handling and exception handling  
- Object-Oriented Programming in Python  
- Practical problem solving and mini projects  
- Foundation for Data Science, Machine Learning, and Automation  

### 💻 C++ with Object-Oriented Programming
- Basics of C++ programming  
- Classes and Objects  
- Encapsulation, Inheritance, Polymorphism  
- Constructors and Destructors  
- Function and Operator Overloading  
- Memory management using pointers and references  
- Writing efficient and structured C++ programs  
OOP-Using-CPP-Lab/
│
├── README.md
│
├── 01_Tokens_Expressions_Control/
│   ├── program_01_add_sub.cpp
│   ├── program_02_swap_third.cpp
│   ├── program_03_swap_no_third.cpp
│   ├── program_04_circle_area_perimeter.cpp
│   ├── program_05_celsius_to_fahrenheit.cpp
│   └── program_06_positive_negative_zero.cpp
│
├── 02_Functions_CPP/
│   ├── call_by_value.cpp
│   ├── call_by_reference.cpp
│   ├── function_overloading.cpp
│   └── inline_function.cpp
│
├── 03_Classes_Objects/
│   ├── simple_class.cpp
│   ├── array_of_objects.cpp
│   └── objects_as_arguments.cpp
│
├── 04_Constructors_Destructors/
│   ├── default_constructor.cpp
│   ├── parameterized_constructor.cpp
│   ├── copy_constructor.cpp
│   └── destructor.cpp
│
├── 05_Operator_Overloading/
│   ├── unary_operator.cpp
│   ├── binary_operator.cpp
│   └── friend_operator.cpp
│
├── 06_Inheritance/
│   ├── single_inheritance.cpp
│   ├── multilevel_inheritance.cpp
│   ├── hierarchical_inheritance.cpp
│   └── virtual_base_class.cpp
│
└── 07_Polymorphism_Pointers/
    ├── pointers_to_objects.cpp
    ├── virtual_function.cpp
    └── pure_virtual_function.cpp

### 🖥️ Operating Systems
- Introduction to Operating Systems  
- Process management and scheduling algorithms  
- CPU scheduling concepts  
- Memory management (paging, segmentation, virtual memory)  
- Deadlocks and synchronization  
- File systems and I/O management  
- Understanding how software interacts with hardware  

### 🎯 Learning Approach
- Concept-first learning with hands-on practice  
- Writing clean, readable, and efficient code  
- Documenting every topic for revision and long-term reference  
- Applying theoretical concepts through implementation  

> These courses form the foundation of my journey toward becoming a strong software engineer with a deep understanding of systems and programming.

Fibonacci Series (n terms)
def fibonacci(n):
    a, b = 0, 1
    for _ in range(n):
        print(a, end=" ")
        a, b = b, a + b

fibonacci(10)



Count Vowels in a String
def count_vowels(s):
    vowels = "aeiouAEIOU"
    return sum(1 for char in s if char in vowels)

print(count_vowels("Artificial Intelligence"))


Find Maximum Element in a List
def find_max(arr):
    max_val = arr[0]
    for num in arr:
        if num > max_val:
            max_val = num
    return max_val

print(find_max([10, 25, 5, 60, 12]))





Linear Search
def linear_search(arr, key):
    for i in range(len(arr)):
        if arr[i] == key:
            return i
    return -1

print(linear_search([4, 7, 1, 9, 3], 9))


Factorial Using Recursion
def factorial(n):
    if n == 0 or n == 1:
        return 1
    return n * factorial(n - 1)

print(factorial(5))
