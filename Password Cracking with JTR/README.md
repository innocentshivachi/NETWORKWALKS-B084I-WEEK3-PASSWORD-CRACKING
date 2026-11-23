# WEEK 3: PASSWORD CRACKING WITH JOHN THE RIPPER (JTR)

**Cybersecurity & Ethical Hacking – Networkwalks**

## 1. Project Overview

This project involved performing a practical password recovery exercise using John the Ripper (JTR) and its graphical user interface, Johnny.

The objective was to recover the password of a password-protected PDF document (`My Locked PDF1.pdf`) using password hash extraction and password-cracking techniques.

The exercise provided hands-on experience with password security, PDF encryption, hash extraction, and the use of password auditing tools.

The lab explored both the command-line version of John the Ripper and Johnny, its graphical interface.

## 2. Objectives

The main objectives of this exercise were:

- Understand how password cracking tools work.
- Install and configure John the Ripper on Windows.
- Install and configure Johnny GUI.
- Understand password-protected PDF documents.
- Extract password hashes from an encrypted PDF file.
- Use John the Ripper to attempt password recovery.
- Understand the importance of strong passwords and secure file protection.

## 3. Tools and Technologies Used

| Tool | Purpose |
|---|---|
| John the Ripper (JTR) | Password auditing and recovery |
| Johnny GUI | Graphical interface for John the Ripper |
| PDF Hash Extractor | Extracting password hashes from protected PDF documents |
| Windows PC | Main testing environment |
| Password-protected PDF | Target document used in the authorized lab |

## 4. Lab Environment

**Operating System:** Windows

**Primary Tool:** John the Ripper

**Graphical Interface:** Johnny

**Target File:** My Locked PDF1.pdf

**Exercise Type:** Password Recovery / Password Security Testing

## 5. Methodology and Practical Implementation

### Step 1: Downloading John the Ripper

The first step involved downloading John the Ripper from its official website.

Official website:

https://www.openwall.com/john/

After downloading the package, the files were extracted to the computer.

The `john.exe` executable was located inside the `run` directory.

### Step 2: Installing and Configuring Johnny GUI

Johnny was downloaded from the official Openwall website.

Website:

https://openwall.info/wiki/john/johnny

After installation, Johnny was opened and configured.

The John the Ripper executable (`john.exe`) was selected through the settings menu to connect Johnny with the underlying John the Ripper installation.

This configuration allowed the graphical interface to communicate with the password-cracking engine.

### Step 3: Preparing the Protected PDF

The provided password-protected PDF document, `My Locked PDF1.pdf`, was downloaded.

The document served as the target file for the password recovery exercise.

### Step 4: Extracting the PDF Password Hash

The PDF hash extraction tool was used to extract the password hash from the protected document.

Website:

https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php

The PDF was uploaded to the extraction tool, which generated a password hash.

The generated hash was copied for use in the password recovery process.

An important observation was that the extracted hash needed to be in the correct format.

The expected format starts with:

`$pdf$`

Any additional characters that were not part of the actual hash needed to be removed before saving the hash.

### Step 5: Password Recovery Using John the Ripper

The extracted PDF hash was prepared for use with John the Ripper.

John the Ripper was the password-cracking engine used in the exercise, while Johnny provided a graphical interface for interacting with it.

The objective was to identify the original password associated with the extracted PDF hash.

**Recovery Result:** [Insert your actual result here.]

## 6. Key Technical Concepts Learned

### A. Password Hashing

Password hashing involves transforming a password into a hash value.

Password hashes are commonly used in security systems to verify passwords without storing the original plaintext password.

### B. Password Cracking

Password cracking involves testing possible password candidates against a stored password hash to determine whether a candidate matches the original password.

John the Ripper automates this process.

### C. PDF Encryption

PDF encryption protects document contents by requiring the appropriate password or encryption key before access is granted.

The exercise demonstrated how password hashes can be extracted from protected PDF documents for authorized security testing.

### D. John the Ripper and Johnny

John the Ripper provides the underlying password-cracking functionality.

Johnny provides a graphical interface that makes it easier for beginners to interact with John the Ripper.

## 7. Screenshots and Practical Evidence

The following screenshots are intended to document the actual implementation and demonstrate the different stages of the exercise.

### Screenshot 1: John the Ripper Download

![John the Ripper](screenshots/01-john-download.png)

Shows the downloaded John the Ripper package.

### Screenshot 2: Johnny Installation

![Johnny Installation](screenshots/02-johnny-installation.png)

Shows the Johnny installation process.

### Screenshot 3: Johnny Configuration

![Johnny Configuration](screenshots/03-johnny-configuration.png)

Shows Johnny configured with the location of `john.exe`.

### Screenshot 4: Protected PDF Document

![Protected PDF](screenshots/04-locked-pdf.png)

Shows the password-protected PDF document used in the exercise.

### Screenshot 5: PDF Hash Extraction

![PDF Hash Extraction](screenshots/05-pdf-hash-extraction.png)

Shows the extraction of the PDF password hash.

### Screenshot 6: Extracted Hash

![Extracted Hash](screenshots/06-extracted-hash.png)

Shows the extracted hash in the required `$pdf$` format.

### Screenshot 7: John the Ripper Password Recovery

![John the Ripper Results](screenshots/07-john-recovery.png)

Shows the password recovery process and its actual result.

### Screenshot 8: Final Recovery Verification

![Password Recovery Verification](screenshots/08-recovery-verification.png)

Shows the final verification of the recovered password by attempting to open the protected PDF.

## 8. Challenges and Observations

During the exercise, several important technical considerations were identified:

- John the Ripper requires the correct executable and configuration.
- Johnny needs to be properly linked to the John the Ripper installation.
- PDF password hashes must be extracted in the correct format.
- Additional characters in an extracted hash can cause processing problems.
- Password recovery depends on the password, available cracking techniques, and the resources used.

## 9. Security Lessons Learned

This exercise demonstrated that password-protected documents should use strong and sufficiently complex passwords.

It also highlighted several important security principles:

- Avoid using short or predictable passwords.
- Use unique passwords for sensitive documents.
- Understand the difference between encryption and hashing.
- Regularly evaluate password security.
- Use password auditing tools responsibly and only on authorized files.

## 10. Conclusion

The Week 3 password-cracking exercise provided practical exposure to John the Ripper and Johnny GUI.

Through this exercise, I explored the process of preparing a password-protected PDF, extracting its password hash, and using password auditing tools to attempt password recovery.

The exercise strengthened my understanding of password security, hash extraction, PDF encryption, and the importance of strong authentication practices.

**Training Platform:** Networkwalks

**Module:** Week 3 – Project Module 1

**Project Category:** Cybersecurity / Ethical Hacking

**Tools:** John the Ripper and Johnny GUI

**Environment:** Windows

---

*Disclaimer: This exercise was conducted for educational purposes within an authorized cybersecurity training environment. Password recovery activities should only be performed on files you own or have explicit permission to test.*
