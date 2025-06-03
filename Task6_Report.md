# 🔐 Task 6: Create a Strong Password and Evaluate Its Strength

## 📌 Objective

To understand what makes a password strong or weak by testing various examples using an online password strength checker, analyzing the results, researching attack methods, and documenting best practices for password creation.

---

## 🔐 Passwords Tested and Results

All passwords were tested using https://passwordmeter.com/

| Password Name  | Password           | Score (%) | Complexity | Feedback Summary                            |
|----------------|--------------------|-----------|------------|---------------------------------------------|
| Weak1          | 12345             | 4%        | Weak  | Too short, numeric only, very common        |
| Weak2          | password           | 8%       | Weak  | Dictionary word, all lowercase              |
| Moderate1      | Summer123         | 39%       | Moderate       |Seasonal word, decent length                |                     |
| Moderate2      | qwerty123          | 41%       | Moderate     | No symbols, predictable                |
| Strong1        | Hell0@000     | 88%       | Strong     | Mix of cases, symbols, numbers              |
| Strong2        | RzCYkcQqzlt??    | 92%       | Strong     | contains uppercase, lowercase, and special characters              |
| VeryStrong1    | T$4pQ!zR7b#W9mA2   | 100%      | Very Strong| Randomized, 16 chars, symbols + numbers     |
| VeryStrong2    | x@9V&jL!rN$5bUw3   | 100%      | Very Strong| High entropy, complex and secure            |

---

## 🔍 Password Categories and Examples

### 🔓 Weak Passwords
Examples: `123456`, `password`  
> **Issues:** Very short, dictionary-based, common, easily cracked by brute force or dictionary attack.

### 🟡 Moderate Passwords
Examples: `Summer123`, `qwerty123`  
> **Issues:** Moderate length and some variation, but still predictable or personal.

### 🔵 Strong Passwords
Examples: `Hell0@000`, ` RzCYkcQqzlt??`  
> **Strengths:** Good use of mixed characters, longer length, minimal predictability.

### 🔒 Very Strong Passwords
Examples: `T$4pQ!zR7b#W9mA2`, `x@9V&jL!rN$5bUw3`  
> **Strengths:** High entropy, randomized, 16 characters, highly resistant to attacks.

---

## 🛡️ Common Password Attack Methods

| Attack Type      | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| **Brute Force**  | Tries every possible combination (e.g., `aaaa`, `aaab`, `aaac`, ...)        |
| **Dictionary**   | Uses a preloaded list of common passwords (e.g., `123456`, `password`, etc.)|
| **Phishing**     | Tricks users into revealing passwords using fake websites or emails         |

**Weak passwords** are easily guessed in seconds using these methods.  
**Strong passwords** significantly increase the time and effort required, making attacks less effective.

---

## 🧠 Key Learnings and Best Practices

From testing and feedback:

- ✅ Use 12+ characters.
- ✅ Mix uppercase, lowercase, numbers, and symbols.
- ✅ Avoid dictionary words, personal info, or predictable patterns.
- ✅ Consider using a password manager for generating and storing secure passwords.
- ✅ Use different passwords for different accounts.

---

