# NETWORKWALKS B084I – WEEK 3: PASSWORD CRACKING

## 1. Project Overview

This repository documents my practical learning activities for **Networkwalks B084I Week 3 – Password Cracking**.

The project focuses on understanding password cracking, PDF password protection, hash extraction, and the techniques used to recover passwords from protected files.

Password cracking is the process of attempting to recover a password by testing possible password combinations against password-related data. It is an important concept in cybersecurity because it helps security professionals evaluate password strength, identify weak authentication practices, and understand the risks associated with easily guessable passwords.

During this practical exercise, I explored two different approaches to password cracking:

- Using **John the Ripper (JTR)** with its graphical interface, Johnny.
- Using **Networkwalks online Hash Calculator and Password Cracker**.

Both approaches involved working with a password-protected PDF file named `My Locked PDF1.pdf`.

## 2. Project Objectives

The main objectives of this practical exercise were:

- Understand the fundamentals of password cracking.
- Understand the relationship between encryption and hashing.
- Learn how to extract password-related hash data from a protected PDF.
- Explore John the Ripper and its Johnny graphical interface.
- Understand how online password-cracking tools operate.
- Learn how to submit extracted hashes to password-cracking tools.
- Attempt to recover a password from a protected PDF.
- Verify the recovered password by opening the original PDF.
- Understand why strong and complex passwords are important for information security.

## 3. Tools and Technologies Used

| Tool / Technology | Purpose |
|---|---|
| John the Ripper (JTR) | Password auditing and recovery attempts. |
| Johnny | Graphical interface for John the Ripper. |
| Networkwalks Hash Calculator | Extracting PDF hash data. |
| Networkwalks Password Cracker | Attempting password recovery using an extracted hash. |
| Online Hash Crack PDF Hash Extractor | Alternative tool for extracting PDF hash data. |
| Windows | Primary lab environment. |
| Kali Linux | Alternative Linux environment. |
| Web Browser | Accessing online cybersecurity tools. |
| Notepad | Preparing and saving extracted hashes in text files. |
| Protected PDF | Target file used in the authorized lab exercise. |

## 4. Practical Exercises

This repository is divided into two main practical exercises.

### Exercise 1: Password Cracking with John the Ripper (JTR)

This exercise introduced me to John the Ripper, a password-auditing tool used to test password strength and recover passwords from supported hash formats.

I explored how to use Johnny, the graphical interface for John the Ripper, to perform password recovery against a protected PDF.

The practical activities included:

1. Downloading and installing John the Ripper.
2. Downloading and installing Johnny.
3. Configuring Johnny to locate the `john.exe` executable.
4. Downloading the password-protected PDF.
5. Extracting the PDF hash using an online PDF hash extraction tool.
6. Preparing the extracted hash in a text file named `hash1.txt`.
7. Loading the hash file into Johnny.
8. Starting a new password recovery attack.
9. Testing the recovered password against the original PDF.

**Key Learning Outcome:**

I learned how to prepare an extracted PDF hash and use John the Ripper through Johnny to attempt password recovery.

### Exercise 2: Password Cracking with Networkwalks Tools

This exercise introduced me to Networkwalks' browser-based password-cracking tools.

Unlike the first exercise, this approach did not require installing John the Ripper or Johnny. The process was performed using online tools.

The practical activities included:

1. Downloading the provided encrypted PDF file.
2. Opening the Networkwalks Hash Calculator.
3. Uploading the protected PDF.
4. Extracting the PDF hash.
5. Copying the complete hash value.
6. Opening the Networkwalks Password Cracker.
7. Submitting the extracted hash.
8. Starting the password-cracking process.
9. Obtaining the recovered password.
10. Opening the original PDF to verify the password.

**Key Learning Outcome:**

I learned how online tools can be used to extract password-related hash data and attempt to recover passwords from protected PDF documents.

## 5. Understanding Important Concepts

### Password Cracking

Password cracking involves testing possible passwords against stored password data or a password-related representation extracted from a protected file.

It is used in authorized security assessments to evaluate password strength and identify weaknesses.

### Hashing

Hashing is a one-way cryptographic process that transforms input data into a hash value.

In password-cracking exercises, tools can use extracted hash data to test possible password candidates.

### Encryption

Encryption protects information by transforming readable data into an unreadable form using a cryptographic algorithm and key.

Unlike hashing, encryption is designed to allow the original information to be recovered when the appropriate key is available.

### PDF Hash Extraction

PDF hash extraction involves obtaining password-related data from a protected PDF so that a compatible password-auditing tool can attempt password recovery.

### Brute-Force and Dictionary Attacks

- **Brute-force attack:** Tests possible character combinations until a matching password is found.
- **Dictionary attack:** Tests passwords from a predefined list of commonly used words and password combinations.

The exact attack strategy depends on the tool and its configuration.

## 6. Comparison of the Two Approaches

| Feature | John the Ripper | Networkwalks Tools |
|---|---|---|
| Platform | Windows / Linux | Web browser |
| Installation | Requires installation | No local installation required |
| Interface | Command-line tool with Johnny GUI | Web-based interface |
| Hash extraction | Requires a compatible extraction method | Networkwalks Hash Calculator |
| Password recovery | John the Ripper | Networkwalks Password Cracker |
| Main learning area | Using a password-auditing tool | Understanding browser-based password-cracking workflows |

Both approaches demonstrate how extracted PDF hash data can be used in password recovery attempts.

## 7. Skills and Knowledge Gained

Through these practical exercises, I gained exposure to:

- Password security fundamentals.
- Password-cracking concepts and techniques.
- PDF password protection.
- Hash extraction and preparation.
- John the Ripper installation and configuration.
- Using Johnny as a graphical interface.
- Working with browser-based cybersecurity tools.
- Understanding brute-force and dictionary attacks.
- Verifying recovered passwords.
- Recognizing the importance of strong passwords.

## 8. Security Lessons

This exercise demonstrated several important password-security lessons:

- Short and commonly used passwords are easier to guess.
- Longer and more complex passwords generally provide better protection.
- Password-protected files should use strong, unique passwords.
- Password security is an important part of protecting sensitive information.
- Password-cracking tools can be useful for identifying weak passwords during authorized security assessments.
- Extracted hashes and sensitive documents should be handled carefully.

## 9. Conclusion

The Networkwalks B084I Week 3 Password Cracking practical exercise provided hands-on exposure to password recovery techniques and the security concepts behind them.

By working with John the Ripper and Johnny, as well as Networkwalks' online Hash Calculator and Password Cracker, I explored two different approaches to recovering passwords from protected PDF documents.

The exercises helped me understand how password-related hash data is extracted, how password candidates are tested, and why strong passwords are essential for protecting information.

Overall, this practical strengthened my understanding of password security, hash extraction, and the use of password-auditing tools in cybersecurity.

## 10. Ethical Considerations

All password-cracking activities documented in this repository are intended for educational purposes and authorized security testing.

Password-cracking techniques should only be performed on files, accounts, and systems that you own or have explicit permission to assess.

Sensitive documents, extracted hashes, and recovered passwords should not be shared publicly.

---

## Repository Structure

```text
NETWORKWALKS-B084I-WEEK3-PASSWORD-CRACKING/
│
├── README.md
│
├── Password Cracking with JTR/
│   └── [JTR practical files and screenshots]
│
└── Password Cracking with NW Tools/
    └── [Networkwalks tools practical files and screenshots]
```

**Training:** Networkwalks B084I  
**Week:** 3  
**Topic:** Password Cracking  
**Category:** Cybersecurity / Password Security  
**Environment:** Windows and Kali Linux  
**Practical Tools:** John the Ripper, Johnny, Networkwalks Hash Calculator and Password Cracker
