# Robot Framework Basics

A beginner-friendly automation test project using **Robot Framework** with **SeleniumLibrary** to test basic web functionality.

## 🚀 Project Overview

This project was created to practice writing UI test cases using a keyword-driven approach with Robot Framework. It focuses on fundamental concepts like:

- Writing test cases using `.robot` files
- Using built-in and external libraries like SeleniumLibrary
- Understanding test structure (Suite, Test Case, Keywords, Variables)

## Features Tested

- Launching a browser and navigating to a URL
- Locating web elements using XPath, ID, and name
- Performing actions like clicking, inputting text, and verifying content
- Simple login form testing

##  Tech Stack

- **Robot Framework**
- **SeleniumLibrary**
- **Python 3.x**
- **ChromeDriver**

## 📥 Installation

1. Clone this repo  
   `git clone https://github.com/bewishguy/robot-framework-basics.git`

2. Create a virtual environment (optional but recommended)  
   `python -m venv venv && source venv/bin/activate` (Linux/macOS)  
   `venv\Scripts\activate` (Windows)

3. Install dependencies  
   `pip install -r requirements.txt`

## ▶️ Run Test

`robot tests/login_test.robot`

## Author Notes
This project was created as part of learning Robot Framework for automation testing. All test logic and structures were written with support from AI-assisted guidance and customized based on learning needs.

"Inspired by YouTube tutorial by [https://youtu.be/h78o6D1RjNc?si=TuxLXINpeOEqVb21] for learning purposes."
