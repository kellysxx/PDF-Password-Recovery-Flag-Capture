# 🔐 PDF Password Recovery & Flag Capture

## 1. Project Overview

This project documents a practical cybersecurity challenge completed during my training with **Networkwalks Academy**.

The objective was to investigate a password-protected PDF document, extract its password hash, use John the Ripper to attempt password recovery, and successfully access the document to capture the challenge flag.

This exercise provided hands-on experience with password security, hash extraction, and password auditing techniques.

## 2. Objectives

- Identify a password-protected PDF document.
- Extract the PDF password hash.
- Use John the Ripper to attempt password recovery.
- Access the protected PDF document.
- Successfully capture the challenge flag.
- Document the investigation process and findings.

## 3. Tools and Technologies

| Tool | Purpose |
|---|---|
| Kali Linux | Cybersecurity testing environment |
| PDF Hash Extractor | Extracting the PDF password hash |
| John the Ripper | Password recovery and auditing |
| Wordlist | Testing possible password combinations |

## 4. Methodology

### Step 1: Identifying the Locked PDF

I received a password-protected PDF document as part of the cybersecurity challenge. The document required a password before its contents could be accessed.

### Step 2: Extracting the PDF Hash

I used an online PDF Hash Extractor website to extract the password hash from the protected PDF document.

The extracted hash was prepared for analysis using John the Ripper.

### Step 3: Password Recovery Using John the Ripper

I used John the Ripper in Kali Linux to perform a password recovery attempt against the extracted hash.

This demonstrated how password-auditing tools use candidate passwords and wordlists to test password hashes.

### Step 4: Accessing the Protected PDF

After successfully recovering the password, I used it to unlock and access the challenge PDF.

### Step 5: Capturing the Flag

After accessing the document, I located the challenge flag and successfully captured Flag 1.

This confirmed that I had completed the challenge successfully.

## 5. Evidence and Screenshots

The following screenshots will document the practical steps performed during the challenge:

- Original password-protected PDF.
- PDF Hash Extractor website.
- John the Ripper password recovery process.
- Successful flag capture confirmation.

## 6. Skills Demonstrated

- Kali Linux command-line operations.
- PDF password hash extraction.
- John the Ripper usage.
- Password auditing techniques.
- Dictionary-based password recovery.
- Cybersecurity investigation and documentation.
- Problem-solving and technical analysis.

## 7. Lessons Learned

Through this challenge, I gained a better understanding of how password-protected PDF documents work, how password hashes can be extracted, and how tools such as John the Ripper can be used for authorized password auditing.

I also learned the importance of strong passwords and secure password management.

## 8. Conclusion

This practical exercise strengthened my cybersecurity knowledge and provided valuable experience working with password recovery tools in Kali Linux.

It was another important step in my cybersecurity learning journey.

## 9. Training Credit

**Training Provider:** Networkwalks Academy

**Challenge:** PDF Password Recovery and Flag Capture

---

**Disclaimer:** This project is for educational purposes and documents activities performed within an authorized cybersecurity training environment. Password recovery techniques should only be used on files you own or have permission to test.

*Note: Actual passwords and challenge flags are intentionally excluded from this public documentation.*
