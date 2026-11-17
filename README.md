# 🔐 PDF Password Recovery & Flag Capture

## Project Overview

This project documents a practical PDF password recovery exercise completed as part of my cybersecurity learning journey. The objective was to explore different methods of extracting PDF password hashes and recovering passwords through dictionary-based attacks.

## Objectives

- Understand how password-protected PDF files work.
- Extract PDF password hashes using different tools.
- Perform dictionary-based password recovery.
- Capture the challenge flag after successfully completing the exercise.

## Tools and Methods Used

1. Networkwalks Free Tools
   - Hash Calculator
   - Password Cracker (Dictionary Attack)

2. PDF Hash Extractor Website

3. John the Ripper

## Methodology

### Method 1: Networkwalks Free Tools

For the first approach, I used the free tools provided by Networkwalks.

**Step 1: Hash Calculator**

I used the Networkwalks Hash Calculator to process the password-protected PDF and obtain the hash required for the recovery process.

**Step 2: Password Cracker – Dictionary Attack**

I used the Networkwalks Password Cracker to perform a dictionary-based attack. The tool tested password candidates from a dictionary against the extracted hash to attempt password recovery.

### Method 2: PDF Hash Extractor and John the Ripper

For the second approach, I used a separate PDF hash extraction website and John the Ripper.

**Step 1: PDF Hash Extraction**

I uploaded the protected PDF to a PDF Hash Extractor website to obtain its password hash.

**Step 2: Password Recovery with John the Ripper**

I used John the Ripper to perform a dictionary-based password recovery process. It tested candidate passwords from a wordlist against the extracted hash.

## Results and Evidence

The exercise provided practical experience with two different PDF password recovery approaches.

Screenshots of the process and challenge completion can be added to the `screenshots/` folder.

## Skills Learned

- PDF hash extraction
- Password recovery techniques
- Dictionary-based password attacks
- Using online cybersecurity tools
- Practical use of John the Ripper
- Understanding password security and weak passwords
- Documenting cybersecurity lab exercises

## Conclusion

This exercise helped me understand how PDF password hashes can be extracted and how dictionary attacks can be used in password recovery. Using two different approaches improved my practical understanding of password security tools and techniques.

## Disclaimer

This project was completed for educational and cybersecurity training purposes in an authorized lab environment. These techniques should only be used on files you own or have explicit permission to test.


