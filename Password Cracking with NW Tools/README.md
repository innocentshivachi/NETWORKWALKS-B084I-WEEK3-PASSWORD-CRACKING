
# Networkwalks Week 3 – Password Cracking Using Networkwalks Tools

## 1. Background

Password cracking is the process of recovering a password from stored data or a protected file. Security professionals use password-cracking techniques to assess password strength and demonstrate the risks associated with weak passwords.

Files such as PDF, ZIP, and Microsoft Office documents can be protected using passwords. In this practical exercise, I used Networkwalks' online Hash Calculator and Password Cracker to extract password-related hash data from a protected PDF and attempt to recover its password.

The exercise demonstrates how password cracking works and why strong passwords are important for information security.

## 2. Objective

To recover the password of the provided protected PDF file (`My Locked PDF1.pdf`) using Networkwalks' Hash Calculator and Password Cracker.

## 3. Tools Used

| Tool | Purpose |
|---|---|
| Networkwalks Hash Calculator | Extracts the PDF hash. |
| Networkwalks Password Cracker | Attempts to recover the PDF password. |
| Web Browser | Accesses the online tools. |
| Notepad (optional) | Temporarily stores the extracted hash. |
| Protected PDF | File used for the practical exercise. |

## 4. Practical Implementation

### Step 1: Download the Encrypted PDF

I visited the Networkwalks project task page and downloaded the provided password-protected PDF file, named `My Locked PDF1.pdf`.

[Networkwalks Password Cracking Lab](https://networkwalks.com/project-task-lab-password-cracking-with-networkwalks-tools/)

![Downloaded Protected PDF](screenshots/01-locked-pdf.png)

### Step 2: Open the Networkwalks Hash Calculator

I opened the Networkwalks Hash Calculator using a web browser.

[Networkwalks Hash Calculator](https://networkwalks.com/hash-calculator/)

![Networkwalks Hash Calculator](screenshots/02-hash-calculator.png)

### Step 3: Upload the Protected PDF

I uploaded the downloaded PDF file to the Hash Calculator. The tool processed the file and generated a hash value.

![PDF Hash Extraction](screenshots/03-pdf-upload.png)

### Step 4: Copy the Extracted Hash

After the extraction process, I copied the complete hash value.

The extracted hash begins with `$pdf$`. I ensured that I copied the entire value without leaving out any characters.

![Extracted PDF Hash](screenshots/04-extracted-hash.png)

### Step 5: Open the Networkwalks Password Cracker

I opened the Networkwalks Password Cracker in my web browser.

[Networkwalks Password Cracker](https://networkwalks.com/password-cracker/)

![Networkwalks Password Cracker](screenshots/05-password-cracker.png)

### Step 6: Submit the Hash

I pasted the extracted PDF hash into the Password Cracker and started the password-cracking process.

![Hash Submitted for Cracking](screenshots/06-hash-submitted.png)

### Step 7: Wait for Password Recovery

The Password Cracker attempted different password candidates against the supplied hash.

The time required depends on the password's complexity and the tool's capabilities.

![Password Recovery Process](screenshots/07-password-recovery.png)

### Step 8: Obtain the Recovered Password

After the cracking process, the tool displayed the recovered password.

I recorded the result for the next verification step.

![Recovered Password](screenshots/08-recovered-password.png)

### Step 9: Verify the Password

I opened the original protected PDF file and entered the recovered password.

The document opened successfully, confirming that the recovered password was correct.

![Successfully Opened PDF](screenshots/09-pdf-opened.png)

## 5. Key Concepts Learned

**Password Cracking:** The process of testing possible passwords to recover a password associated with a protected file or stored password data.

**Hash Extraction:** Obtaining password-related hash data from a protected file so that it can be used in a password-cracking process.

**Hashing:** A one-way process that transforms input data into a hash value.

**Encryption:** A process that protects information by transforming it into an unreadable form. The appropriate cryptographic key is required to recover the original information.

**Password Strength:** Strong passwords make unauthorized password recovery more difficult. Using longer passwords with a mixture of character types can improve security.

## 6. Results

| Activity | Result |
|---|---|
| Downloaded protected PDF | [Completed / Not completed] |
| Extracted PDF hash | [Completed / Not completed] |
| Submitted hash to Password Cracker | [Completed / Not completed] |
| Recovered password | [Successful / Unsuccessful] |
| Verified password by opening PDF | [Successful / Unsuccessful] |

## 7. Conclusion

This practical exercise introduced me to password cracking using Networkwalks' online security tools. I learned how to obtain a hash from a password-protected PDF, submit it to a password-cracking tool, and verify the recovered password against the original document.

The exercise also demonstrated why password complexity is important in protecting sensitive files and information.

## 8. Ethical Considerations

Password-cracking tools should only be used on files and systems that I own or have explicit permission to test. This exercise was conducted for educational purposes using the PDF provided for the lab.

---

**Project:** Networkwalks Week 3 – Password Cracking Using Networkwalks Tools  
**Category:** Cybersecurity / Password Security  
**Environment:** Windows or Kali Linux  
**Tools:** Networkwalks Hash Calculator and Password Cracker
