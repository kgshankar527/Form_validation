# 🌐 Registration Form Validation  

[![HTML](https://img.shields.io/badge/Language-HTML-orange?logo=html5)](#)  
[![CSS](https://img.shields.io/badge/Style-CSS-blue?logo=css3)](#)  
[![JavaScript](https://img.shields.io/badge/Script-JavaScript-yellow?logo=javascript)](#)  
[![Status](https://img.shields.io/badge/Status-Completed-success)](#)  
[![Live Demo](https://img.shields.io/badge/Live-Demo-blue)](https://kgshankar527.github.io/Form_validation/)  

---

## 📌 Overview
This is a **Registration Form Validation Project** built with **HTML, CSS, and JavaScript**.  
It validates user inputs such as **User ID, Email, Contact Number, and Password** with both basic and advanced rules.  

---

## 🚀 Features
- ✅ User ID validation (not empty)  
- ✅ Email validation (`example@gmail.com` format)  
- ✅ Contact number must be **10 digits** (only numbers)  
- ✅ Password strength check:
  - At least 8 characters  
  - 1 Uppercase (A–Z)  
  - 1 Lowercase (a–z)  
  - 1 Number (0–9)  
  - 1 Special character (`@ $ ! % * ? &`)  
- ✅ Confirm Password must match Password  
- ✅ Alert messages for invalid inputs  
- ✅ Redirects to `abc.html` on success  

---

## 🎯 Example Input

| Field             | Valid Example    | Invalid Example  |
|-------------------|-----------------|-----------------|
| User ID           | `kgshankar527`  | *(empty)*       |
| Email             | `abc@gmail.com` | `abc@com`       |
| Contact Number    | `9876543210`    | `98765abc10`    |
| Password          | `Abcd@1234`     | `abcd1234`      |
| Confirm Password  | `Abcd@1234`     | `Abcd123`       |

---

## 🖼️ Preview (Screenshot Placeholder)

![Preview Screenshot](https://via.placeholder.com/800x400?text=Form+Validation+Preview)

*(Replace this link with your actual screenshot once ready)*

---

## 📂 Project Structure

- `index.html` → Registration Form
- `style.css`  → Form style code
- `main.js`   → Validation Script
- `random.md` → Documentation (This File)
- `abc.html` → Redirect success page (dummy page) Data Store

---

## ⚡ How It Works
1. User fills out the form.  
2. On clicking **Submit**, the JavaScript function `data()` runs.  
3. It checks:
   - Empty fields  
   - Valid email  
   - 10-digit contact number  
   - Password strength  
   - Password match  
4. If validation fails → an `alert()` shows the error.  
5. If all good → `"✅ Form submitted successfully!"` appears and user is redirected to `abc.html`.  

---

## 📜 Version
- **v1.0.0** — Initial release with validation rules  

---

## ✍️ Author
**Gauri Shankar Katara (kgshankar527)**  

🔗 GitHub: [kgshankar527](https://github.com/kgshankar527)  
📅 Year: 2025  

---

⭐ *If you like this project, give it a star on GitHub!* ⭐
