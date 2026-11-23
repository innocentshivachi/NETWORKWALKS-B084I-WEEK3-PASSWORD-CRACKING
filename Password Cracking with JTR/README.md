# WEEK 3 – PROJECT MODULE 1: PASSWORD CRACKING WITH JOHN THE RIPPER (JTR)

**Cybersecurity & Ethical Hacking | Networkwalks**

---

## 1. Project Overview

This project involved performing a practical password recovery exercise using **John the Ripper (JTR)** and its graphical interface, **Johnny GUI**.

The objective was to recover the password of a protected PDF document (`My Locked PDF1.pdf`) through password hash extraction and password-cracking techniques.

The exercise provided hands-on experience with password security, PDF encryption, hash extraction, and the use of password auditing tools.

Both the command-line version of John the Ripper and its graphical interface were explored during this exercise.

## 2. Project Objectives

The main objectives of this exercise were:

- Understand how password-cracking tools work.
- Download and configure John the Ripper.
- Install and configure Johnny GUI.
- Understand password-protected PDF documents.
- Extract password hashes from an encrypted PDF.
- Perform password recovery using John the Ripper.
- Understand the importance of strong passwords and document security.

## 3. Tools and Technologies Used

| Tool | Purpose |
|---|---|
| John the Ripper | Password auditing and recovery |
| Johnny GUI | Graphical interface for John the Ripper |
| PDF Hash Extractor | Extracting password hashes from PDF documents |
| Windows PC | Testing environment |
| Protected PDF | Target document for the exercise |

## 4. Practical Implementation

### STEP 1: Downloading John the Ripper

The first step involved downloading John the Ripper from the official Openwall website.

John the Ripper is an open-source password security auditing tool capable of testing password hashes against different password candidates.

**Download source:** https://www.openwall.com/john/

After downloading the package, the files were extracted to the computer.

The `john.exe` executable was located inside the `run` directory.

**Screenshot Evidence:**

![John the Ripper Download](screenshots/01-john-download.png)

*Figure 1: Downloaded John the Ripper package.*

---

### STEP 2: Downloading and Installing Johnny GUI

The next step involved downloading Johnny, the graphical user interface for John the Ripper.

Johnny provides a point-and-click interface that makes interacting with the password-cracking engine easier.

**Download source:** https://openwall.info/wiki/john/johnny

After downloading the setup file, Johnny was installed on the Windows computer.

**Screenshot Evidence:**

![Johnny Installation](screenshots/02-johnny-installation.png)

*Figure 2: Johnny GUI installation.*

---

### STEP 3: Configuring Johnny with John the Ripper

After installing Johnny, the application was opened and configured to use the John the Ripper executable.

The following configuration process was performed:

1. Open Johnny.
2. Navigate to Settings.
3. Browse for the John the Ripper executable.
4. Locate the `john.exe` file inside the `run` directory.
5. Select the executable.

This configuration connects Johnny's graphical interface to the underlying John the Ripper engine.

**Screenshot Evidence:**

![Johnny Configuration](screenshots/03-johnny-configuration.png)

*Figure 3: Configuring Johnny to locate john.exe.*

---

### STEP 4: Preparing the Password-Protected PDF

The next stage involved obtaining the encrypted PDF document provided for the exercise.

**Target file:** `My Locked PDF1.pdf`

The document was used as the target for the password recovery exercise.

The purpose was to obtain the password hash associated with the protected PDF before attempting password recovery.

**Screenshot Evidence:**

![Protected PDF](screenshots/04-locked-pdf.png)

*Figure 4: Password-protected
