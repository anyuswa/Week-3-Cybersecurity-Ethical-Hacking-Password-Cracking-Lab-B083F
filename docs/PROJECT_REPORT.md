# Project Report — Week 3 Password Cracking Lab

## 1. Executive Summary

This report documents the practical completion of Week 3 Project Module 1: Password Cracking with John the Ripper (JTR), followed by Week 3 Project Module 2: Password Cracking with Networkwalks Tools.

Module 1 demonstrates extracting a PDF password hash, saving it in a text file, loading it into Johnny, starting an attack and using the recovered password to open a protected PDF.

Module 2 demonstrates extracting a PDF hash with the Networkwalks Hash Calculator, submitting it to the Networkwalks Password Cracker, recovering the corresponding password and using it to open the supplied protected PDF.

Both activities are documented as authorized cybersecurity training exercises.

## 2. Module 1 — John the Ripper (JTR)

### Task overview

The practical objective was to crack the password of an attached protected PDF using John the Ripper and the Johnny graphical interface on a Windows PC.

### Objectives

- Prepare John the Ripper and Johnny.
- Configure Johnny to use `john.exe`.
- Obtain the hash representation of the encrypted training PDF.
- Save the extracted hash in the required text format.
- Load the hash into Johnny.
- Start a password-cracking attack.
- Document the result.
- Use the recovered password to open the protected PDF.
- Provide screenshot evidence for the major stages.

### Methodology

#### 1. Prepare John the Ripper and Johnny

The supplied instructions direct the learner to obtain John the Ripper and Johnny from Openwall. Johnny is configured through its settings so that it points to the `john.exe` executable in the JTR run folder.

#### 2. Configure Johnny

Open Johnny, select **Settings**, browse to the JTR `john.exe` executable and confirm the configuration.

#### 3. Obtain the PDF hash

The encrypted training PDF is processed using the specified PDF hash-extraction workflow. The resulting hash is copied for use with JTR.

#### 4. Create `hash1.txt`

The extracted hash is pasted into a text editor and saved as `hash1.txt`. The supplied instructions specify removing extra characters such as `b'` and retaining the expected `$pdf$...` format.

#### 5. Load the hash into Johnny

Use **Open password file** in Johnny and select `hash1.txt`.

#### 6. Start the attack

Select **Start new attack**. The cracking time depends on computer performance and password complexity.

#### 7. Verify the recovered password

Use the recovered password to open the protected PDF and confirm successful access.

### Module 1 results

| Item | Result |
|---|---|
| JTR installed / available | Completed |
| Johnny configured with `john.exe` | Completed |
| PDF hash extracted | Completed |
| `hash1.txt` created | Completed |
| Attack completed | Completed |
| PDF opened successfully | Completed |

### Module 1 observations

- Installation / configuration issue: None
- Hash extraction issue: None
- Cracking time observed: not recorded precisely; the report states it was not more than five minutes after setup.
- Password complexity observation: Moderate complexity.

## 3. Module 2 — Networkwalks Tools

### Task overview

The second practical uses the Networkwalks Hash Calculator to extract a password hash from a locked PDF and the Networkwalks Password Cracker to identify the corresponding password.

### Objectives

- Obtain the encrypted PDF specified by the practical.
- Use the Networkwalks Hash Calculator to extract the PDF hash.
- Copy the complete `$pdf$` hash.
- Submit the hash to the Networkwalks Password Cracker.
- Start the cracking process.
- Record the recovered password.
- Use the recovered password to open the locked PDF.

### Methodology

#### Step 1 — Obtain the encrypted PDF

Download the supplied locked PDF identified by the practical task.

#### Step 2 — Open the Hash Calculator

Open the Networkwalks Hash Calculator in a browser.

#### Step 3 — Upload the locked PDF and extract the hash

Upload the PDF. The tool produces a hash beginning with `$pdf$`.

#### Step 4 — Copy the complete hash

Copy the entire generated value, including the initial `$pdf$` portion.

#### Step 5 — Open the Password Cracker

Open the Networkwalks Password Cracker in a browser.

#### Step 6 — Submit the hash and start the attack

Paste the extracted hash into the Password Cracker and start the attack. The practical describes the process as testing candidate passwords until a matching value is found.

#### Step 7 — Record the recovered password

Wait for completion and record the password displayed by the tool.

#### Step 8 — Enter the recovered password

Open the locked PDF in a PDF reader and enter the recovered password.

#### Step 9 — Confirm successful access

Confirm that the password is accepted and that the protected PDF opens.

### Module 2 results

| Item | Result |
|---|---|
| PDF file | My Locked PDF2 |
| Hash extracted | Completed |
| Cracking status | Successful |
| Recovered password | **Redacted in this public repository** |
| PDF access confirmed | Yes |
| Completion date | 24/09/2026 |

> The original report contains the recovered password and a partial PDF hash. Those values have intentionally not been copied into this public-facing repository report because credentials and password-derived material should not be published unnecessarily.

## 4. Evidence Checklist

- [x] Locked PDF downloaded
- [x] Hash Calculator opened
- [x] PDF uploaded to Hash Calculator
- [x] `$pdf$` hash extracted
- [x] Complete hash copied
- [x] Password Cracker opened
- [x] Hash submitted and attack started
- [x] Password recovered
- [x] Password entered into locked PDF
- [x] PDF opened successfully

## 5. Discussion

The exercise demonstrates the relationship between a protected file, a password-derived hash and password-recovery attempts. It illustrates that a password can be vulnerable when it is simple or predictable enough to be identified through systematic password testing.

The supplied material also distinguishes encryption from hashing: encryption is presented as a two-way process in which protected information can be recovered with the appropriate key, while hashing is presented as a one-way transformation into a message digest.

The practical therefore reinforces the importance of strong, unique passwords.

## 6. Ethical and Security Considerations

Password-cracking techniques should only be used on systems, files, accounts or datasets for which the tester has explicit authorization.

This project is framed as a controlled cybersecurity training exercise using supplied laboratory files. Its purpose is to understand password security and demonstrate the risks associated with weak credentials, not to obtain unauthorized access to third-party information.

## 7. Conclusion

The Week 3 practical provides a complete demonstration of password recovery using two different workflows:

- John the Ripper + Johnny
- Networkwalks Hash Calculator + Password Cracker

The documented workflow moves from hash extraction through password testing and ends with verification by opening the protected PDF.

The screenshots included in the repository provide visual evidence of the practical stages.

## 8. References

- Networkwalks — Week 3 Project Module 2: Password Cracking with Networkwalks Tools
- Openwall — John the Ripper: https://www.openwall.com/john/
- Openwall — Johnny: https://openwall.info/wiki/john/johnny
- Networkwalks Hash Calculator: https://networkwalks.com/hash-calculator/
- Networkwalks Password Cracker: https://networkwalks.com/password-cracker/

## Learner Declaration

The original report states that the practical work was performed in an authorized training/lab environment and that the screenshots represent the learner's practical evidence.

**Learner:** Asanda Lloyd Nyuswa  
**Program / Batch:** B083F  
**Date:** 24/09/2026
