# Project Module 1 — Password Cracking with John the Ripper

## Overview

This module documents the Week 3 practical using **John the Ripper (JTR)** and the **Johnny GUI** on a Windows PC.

The stated objective was to recover the password of an encrypted training PDF in an authorized environment.

## Tools

| Tool / Resource | Purpose |
|---|---|
| John the Ripper | Password/hash cracking engine |
| Johnny GUI | Graphical interface for JTR |
| Encrypted training PDF | Lab target |
| Notepad / text editor | Store the extracted hash |
| PDF hash extractor | Extract the PDF hash |

## Procedure

### 1. Prepare John the Ripper and Johnny

John the Ripper and Johnny were prepared, and Johnny was configured to use the `John.exe` executable in the JTR `run` folder.

### 2. Obtain the PDF hash

The encrypted training PDF was processed using the specified PDF hash extraction workflow. The resulting hash was copied for use with JTR.

### 3. Create `hash1.txt`

The extracted hash was placed into a text file named `hash1.txt`. The report notes that the expected format begins with `$pdf$...` and that unwanted characters should be removed.

### 4. Load the hash into Johnny

`hash1.txt` was opened through Johnny using **Open password file**.

### 5. Start the attack

A new password-cracking attack was started through Johnny.

### 6. Verify the recovered password

The recovered password was used to open the protected training PDF. The report records successful access.

## Results

| Item | Result |
|---|---|
| JTR installed / available | Completed |
| Johnny configured with `John.exe` | Completed |
| PDF hash extracted | Completed |
| `hash1.txt` created | Completed |
| Attack completed | Completed |
| PDF opened successfully | Completed |

## Evidence

Evidence pages extracted from the submitted report are available in [`../../evidence/module-1-jtr/`](../../evidence/module-1-jtr/).

## Ethical Considerations

The source report states that password-cracking tools should only be used against files, systems, or accounts for which explicit authorization exists. The target used in this practical was the supplied training PDF.

## Source

See the original report in [`WK_3FinaltaskReport.pdf`](WK_3FinaltaskReport.pdf).
