# 🔓 Password Cracking: Understanding Security and Attack Methods  

## 🔍 Overview  
This project explores the process of password cracking using ethical hacking techniques. It is designed to bridge the gap between technical and non-technical audiences by showcasing real-world password vulnerabilities and best practices for security.  

## 📌 Key Topics  
- 🔑 **Windows Authentication & NTLM Hashing**  
- 📡 **Packet Capture & Hash Extraction with Wireshark**  
- ⚡ **Password Cracking using Hashcat**  
- 🛠️ **Dictionary, Hybrid, and Brute Force Attacks**  
- 🎮 **GPU Acceleration in Password Cracking**  
- 🔐 **Security Recommendations & Best Practices**  

## 🖥️ Tools & Environment  
-  **Windows & Kali Linux Virtual Machines**  
-  **Wireshark for Packet Capture**  
-  **Hashcat for Password Cracking**  
-  **RockYou Wordlist for Dictionary Attacks**  
-  **GPU Acceleration (NVIDIA GTX 1070 Ti Used for Testing)**  

## 🛠️ Attack Demonstrations  
### 1️⃣ Capturing NTLM Hashes  
- Using Wireshark to intercept authentication traffic and extract NTLMv2 password hashes.  

### 2️⃣ Dictionary Attack  
- Running Hashcat against common password lists to crack weak credentials.  

### 3️⃣ Hybrid Attack  
- Combining dictionary words with additional characters to guess more complex passwords.  

### 4️⃣ Brute Force Attack  
- Attempting to crack passwords by testing all possible character combinations.  

## 📊 Results  
- ✅ **Weak passwords (e.g., "sunshine") cracked in seconds.**  
- ⚠️ **Moderate passwords (e.g., "Johnny2311*") cracked with dictionary-based techniques.**  
- 🔒 **Strong passwords (e.g., "O;dC1>}db9I83") resisted all cracking attempts.**  
- 🏗️ **Brute force attacks took an impractical amount of time without significant GPU power.**  

## 🎓 Lessons Learned  
- Short, simple passwords are easily cracked.  
- Length and complexity significantly increase security.  
- GPUs dramatically speed up password cracking but have limits.  
- Proper password hygiene is essential to preventing breaches.  

## 🏁 Conclusion  
This project highlights the importance of password security and demonstrates how attackers exploit weak credentials. By understanding these techniques, users can better protect their accounts from unauthorized access.  

🔹 **Remember:** A strong password is your first line of defense! 🔹  
