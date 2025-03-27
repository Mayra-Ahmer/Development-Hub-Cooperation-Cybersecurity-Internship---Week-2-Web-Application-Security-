## Cybersecurity Internship - Week 2

## 📌 Overview
This repository contains the work completed during **Week 2** of my cybersecurity internship. The focus was on securing a **Node.js web application** by implementing essential security measures.

## 🔐 Security Implementations
### 1️⃣ Input Validation & Sanitization
- Used **Validator.js** to prevent malicious input.
- Ensured email format validation.

### 2️⃣ Password Hashing
- Implemented **bcrypt** for secure password storage.
- Stored only hashed passwords in the database.

### 3️⃣ JWT Authentication
- Used **JSON Web Tokens (JWT)** for user authentication.
- Secrets stored securely in **environment variables (.env)**.

### 4️⃣ Securing HTTP Headers
- Integrated **Helmet.js** to protect against common vulnerabilities.

### 5️⃣ Security Testing & Validation
- Verified server status and security headers using:
  ```sh
  curl -I http://localhost:3000
  ```
- Checked process and listening ports using:
  ```sh
  ps aux | grep node
  netstat -tlnp | grep 3000
  ```

## 🛠️ Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/cybersecurity-week2.git
   cd cybersecurity-week2
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env` file and configure your **JWT_SECRET**.
4. Run the application:
   ```sh
   node app.js
   ```

## 📑 Report Document
The detailed report is available in `Cybersecurity Internship Report week2.docx`.

## 🔗 References
- [OWASP Security Guidelines](https://owasp.org/www-project-top-ten/)
- [Node.js Security Best Practices](https://nodejs.org/en/docs/guides/security/)
