# 🧮 PROJECT OMEGA: Enterprise Grade C++ Calculator

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Language](https://img.shields.io/badge/language-C%2B%2B11-blue)
![Bhai-Approved](https://img.shields.io/badge/quality-Bhai%20Approved-orange)

> "Ye koi aam calculator nahi hai, ye ek *System* hai." - Senior Dev

## 📜 Overview
Welcome to **Project Omega**, the most over-engineered, robust, and aesthetically pleasing terminal-based calculator you will ever see. 

Client ne bola tha "Make it robust", toh humne **Shunting Yard Algorithm** ke saath pura OOP design pattern laga diya. Isme `Lexer`, `Parser`, aur `Evaluator` sab alag modules hain. 700+ lines of pure C++ logic.

## 🚀 Features (Jo isse khaas banate hain)

* **Advanced Math Core**: Basic arithmetic (`+`, `-`, `*`, `/`) se lekar Advanced functions tak sab chalta hai.
* **Scientific Functions**: `sin`, `cos`, `tan`, `sqrt`, `log` (base 10).
* **Smart Parsing**: Uses **Shunting Yard Algorithm** to handle operator precedence like a boss. 
* **Constants Support**: `pi` aur `e` ki values yaad rakhne ki zarurat nahi, bas type karo.
* **History Manager**: Purane paap (calculations) bhoolne nahi deta. Type `history` to see past logs.
* **Error Handling**: "Syntax Error" se lekar "Division by Zero" tak, sab handle hota hai bina crash kiye.
* **Colorful UI**: ANSI color codes use kiye hain taki hacker wali feeling aaye.

## 🛠️ Installation & Compilation

Bhai tere paas `g++` hona chahiye. Nahi hai toh pehle install kar.

1.  **Clone or Download this repo.**
2.  **Compile the code:**
    ```bash
    g++ calculator_pro_max.cpp -o omega_calc
    ```
3.  **Run the beast:**
    * **Linux/Mac:**
        ```bash
        ./omega_calc
        ```
    * **Windows:**
        ```cmd
        omega_calc.exe
        ```

## 📖 Usage Guide

Calculator chalu hote hi `Calc >` prompt aayega. Waha ye sab try kar:

### 1. Basic Math
```text
Calc > 2 + 2 * 4
>> RESULT: 10
