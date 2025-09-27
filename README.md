# 🚀 42 School - C++ Modules Journey

<div align="center">

![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![42 School](https://img.shields.io/badge/42-School-000000?style=for-the-badge&logo=42&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge)
![Progress](https://img.shields.io/badge/Progress-100%25-success?style=for-the-badge)

*A comprehensive journey through C++ fundamentals and advanced concepts*

</div>

## 📖 About

This repository contains my complete implementation of the **42 School C++ Modules (00-09)**, representing a comprehensive journey from C++ basics to advanced programming concepts. Each module builds upon the previous one, introducing new concepts, design patterns, and C++ features.

## 🎯 Learning Objectives

- **Master C++ Fundamentals**: From basic syntax to advanced features
- **Object-Oriented Programming**: Classes, inheritance, polymorphism, and encapsulation
- **Memory Management**: Understanding stack, heap, and RAII principles
- **STL Containers**: Vectors, maps, stacks, and custom implementations
- **Exception Handling**: Robust error handling mechanisms
- **Templates**: Generic programming and metaprogramming
- **Design Patterns**: Factory, Observer, and other essential patterns

## 📚 Module Overview

### 🔰 Module 00 - Namespaces, Classes, Member Functions
**Foundation Building**
- **ex00**: Megaphone - String manipulation and basic I/O
- **ex01**: PhoneBook - Classes, arrays, and user interaction
- **ex02**: Account - Static members and basic banking simulation

**Key Concepts**: Classes, member functions, constructors/destructors, static members

### 🧟 Module 01 - Memory Allocation, References, Pointers
**Memory Mastery**
- **ex00**: BraiiiiiiinnnzzzZ - Dynamic allocation and zombie management
- **ex01**: Moar Brainz! - Arrays and multiple objects
- **ex02**: HI THIS IS BRAIN - References vs pointers
- **ex03**: Unnecessary Violence - Object composition and references
- **ex04**: Sed is for Losers - File manipulation and string replacement
- **ex05**: Harl 2.0 - Function pointers and member functions
- **ex06**: Harl Filter - Switch statements and filtering

**Key Concepts**: Dynamic allocation, references, pointers, file I/O, function pointers

### 🔢 Module 02 - Ad-hoc Polymorphism, Operators, Orthodox Canonical Form
**Operator Excellence**
- **ex00**: My First Orthodox Canonical Class - Basic fixed-point numbers
- **ex01**: Towards Useful Fixed-Point Number Class - Arithmetic operators
- **ex02**: Now We're Talking - Comparison and increment operators
- **ex03**: BSP (Binary Space Partitioning) - Geometric calculations

**Key Concepts**: Operator overloading, Orthodox Canonical Form, fixed-point arithmetic

### ⚔️ Module 03 - Inheritance
**Heritage and Hierarchy**
- **ex00**: Aaaaand... OPEN! - Basic inheritance with ClapTrap
- **ex01**: Serena, My Love! - Derived classes with ScavTrap
- **ex02**: Repetitive Work - Multiple inheritance with FragTrap
- **ex03**: Now It's Weird! - Diamond problem and virtual inheritance

**Key Concepts**: Inheritance, virtual functions, multiple inheritance, diamond problem

### 🦆 Module 04 - Subtype Polymorphism, Abstract Classes, Interfaces
**Polymorphic Power**
- **ex00**: Polymorphism - Abstract Animal classes
- **ex01**: I Don't Want to Set the World on Fire - Deep copying and brain simulation
- **ex02**: Abstract Class - Pure virtual functions and interfaces
- **ex03**: Interface & Recap - Complex interface implementations

**Key Concepts**: Abstract classes, interfaces, virtual destructors, deep copying

### 📝 Module 05 - Exceptions
**Error Handling Excellence**
- **ex00**: Mommy, When I Grow Up, I Want to Be a Bureaucrat! - Basic exceptions
- **ex01**: Form Up, Maggots! - Custom exception classes
- **ex02**: No, You Need Form 28B, Not 28C... - Derived form classes
- **ex03**: At Least This Beats Coffee-Making - Intern and form factories

**Key Concepts**: Exception handling, try-catch blocks, custom exceptions, RAII

### 🔄 Module 06 - Casts
**Type Conversion Mastery**
- **ex00**: Conversion of Scalar Types - Static cast and type conversion
- **ex01**: Serialization - Reinterpret cast and data serialization
- **ex02**: Identify Real Type - Dynamic cast and type identification

**Key Concepts**: Static cast, dynamic cast, reinterpret cast, const cast, type safety

### 🧩 Module 07 - Templates
**Generic Programming**
- **ex00**: Start with a Few Functions - Function templates
- **ex01**: Iter - Template functions with iterators
- **ex02**: Array - Template classes and bounds checking

**Key Concepts**: Function templates, class templates, template specialization, STL basics

### 🧱 Module 08 - Templated Containers, Iterators, Algorithms
**STL Deep Dive**
- **ex00**: Easy Find - STL algorithms and containers
- **ex01**: Span - Custom container implementation
- **ex02**: Mutated Abomination - Stack container adaptations

**Key Concepts**: STL containers, iterators, algorithms, container adaptors

### 🏆 Module 09 - Advanced Containers and Algorithms
**Mastery Achievement**
- **ex00**: Bitcoin Exchange - File parsing and data validation
- **ex01**: Reverse Polish Notation - Stack-based calculator
- **ex02**: PmergeMe - Advanced sorting algorithms comparison

**Key Concepts**: Advanced STL usage, algorithm optimization, performance analysis

## 🛠️ Compilation & Usage

Each exercise includes a `Makefile` with the following targets:
```bash
make        # Compile the program
make clean  # Remove object files
make fclean # Remove object files and executable
make re     # Recompile everything
```

### Compilation Flags
All programs are compiled with:
```bash
c++ -Wall -Wextra -Werror -std=c++98
```

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/melaniereis/42_cpp_modules.git
   cd 42_cpp_modules
   ```

2. **Navigate to any module**:
   ```bash
   cd CPP_Module00/ex00
   ```

3. **Compile and run**:
   ```bash
   make
   ./megaphone "Hello World!"
   ```

## 🎨 Code Quality Standards

- ✅ **C++98 Standard**: Full compliance with C++98 specifications
- ✅ **42 Norm**: Adherence to 42 School coding standards
- ✅ **Orthodox Canonical Form**: Proper implementation where required
- ✅ **Memory Management**: No memory leaks (verified with Valgrind)
- ✅ **Error Handling**: Robust exception handling and input validation
- ✅ **Documentation**: Clear, concise code with meaningful variable names

## 🏗️ Project Structure

```
42_cpp_modules/
├── CPP_Module00/     # Basic C++ concepts
├── CPP_Module01/     # Memory and references
├── CPP_Module02/     # Operators and canonical form
├── CPP_Module03/     # Inheritance
├── CPP_Module04/     # Polymorphism and abstract classes
├── CPP_Module05/     # Exceptions
├── CPP_Module06/     # Casts
├── CPP_Module07/     # Templates
├── CPP_Module08/     # STL containers and iterators
└── CPP_Module09/     # Advanced algorithms and containers
```

## 💡 Key Takeaways

- **RAII Principle**: Resource Acquisition Is Initialization
- **Rule of Three/Five**: Proper resource management in classes
- **DRY Principle**: Don't Repeat Yourself through templates and inheritance
- **SOLID Principles**: Object-oriented design best practices
- **STL Mastery**: Understanding and utilizing the Standard Template Library
- **Performance Awareness**: Algorithm complexity and optimization techniques

## 🧪 Testing

Each module includes comprehensive test cases covering:
- Edge cases and boundary conditions
- Memory leak detection
- Exception safety
- Performance benchmarks (where applicable)

## 📈 Progression Highlights

- **Gradual Complexity**: From simple I/O to advanced template metaprogramming
- **Real-world Applications**: Practical exercises like calculator, phonebook, and data processing
- **Performance Focus**: Algorithm comparison and optimization in later modules
- **Best Practices**: Emphasis on clean, maintainable, and efficient code

## 🤝 Contributing

While this is a personal learning repository, suggestions and discussions about C++ best practices are welcome! Feel free to:
- Report issues or bugs
- Suggest improvements
- Share alternative implementations
- Discuss C++ concepts and techniques

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **42 School** for providing this comprehensive C++ curriculum
- **The C++ Community** for extensive documentation and resources
- **Peers and Mentors** who provided guidance throughout this journey

---

<div align="center">

**Made with ❤️ and lots of ☕ by [melaniereis](https://github.com/melaniereis)**

*"The journey of a thousand programs begins with a single class."*

</div>
