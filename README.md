# Registration Form Validation ✅

यह एक simple **HTML + JavaScript Project** है जिसमें basic से लेकर advanced validation तक जोड़े गए हैं।  

---

## 🔹 Features
1. **User ID Validation**
   - Empty नहीं होना चाहिए।

2. **Email Validation**
   - Must follow standard format: `example@gmail.com`.

3. **Contact Number Validation**
   - Exactly **10 digits** होना चाहिए।
   - केवल numbers allow हैं।

4. **Password Validation**
   - कम से कम 8 characters।
   - 1 Uppercase (A–Z)।
   - 1 Lowercase (a–z)।
   - 1 Number (0–9)।
   - 1 Special Character (`@ $ ! % * ? &`)।

5. **Confirm Password**
   - Password और Confirm Password दोनों match होने चाहिए।

---

## 🔹 Example Input

| Field             | Valid Example          | Invalid Example      |
|-------------------|------------------------|----------------------|
| User ID           | `kgshankar527`         | `` (empty)          |
| Email             | `abc@gmail.com`        | `abc@com`           |
| Contact Number    | `9876543210`           | `98765abc10`        |
| Password          | `Abcd@1234`            | `abcd1234`          |
| Confirm Password  | `Abcd@1234`            | `Abcd123`           |

---

## 🚀 How It Works
1. User form भरता है।
2. `Submit` बटन दबाने पर **JavaScript function `data()`** call होता है।
3. Function सभी inputs को check करता है:
   - Empty fields
   - Email format
   - Contact number length और numeric check
   - Password strength
   - Confirm password match
4. अगर कोई error है → `alert()` message show होता है।
5. अगर सब valid है → `"✅ Form submitted successfully!"` message दिखता है और user को `abc.html` पर redirect किया जाता है।

---

## 📂 Files
- `index.html` → Registration Form + Validation Script
- `random.md` → Documentation (This File)
- `abc.html` → Redirect success page (dummy page)

---

✍️ **Author**: `kgshankar527`  
📅 **Version**: 1.0.0
