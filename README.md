# Python interface in C++ project via Pybind11 (Minimal demo)

## How C++ provide Python interface?

### The idea 

1. The program creates a Python interpreter so that it can execute Python code. 

2. The program then retrives the method from the Python source file and prepares
the arguments that will be sent to the m
   
### The methods


* Ctypes: wrap calls to basic C function and primitive data types
  
* Boost.Python: C++ and python binding, boost module

* Pybind11: header only, it supports C++11 and STL which makes life easier to pass 
  on basic data structure without writing any code
  
### Preparation

#### Get Pybind11

```
git submodule add -b stable git@github.com:pybind/pybind11.git extern/pybind11
```


   
   