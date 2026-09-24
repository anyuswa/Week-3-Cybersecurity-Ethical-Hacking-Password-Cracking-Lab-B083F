# Project Module 2 — Password Cracking with Networkwalks Tools

## Overview

This module documents the Week 3 practical using the **Networkwalks Hash Calculator** and **Networkwalks Password Cracker**.

The practical used a protected PDF in a controlled cybersecurity training environment.

## Tools

| Resource | Purpose |
|---|---|
| Networkwalks project task page | Source of the practical task and encrypted PDF |
| Networkwalks Hash Calculator | Extract the password-protected PDF hash |
| Networkwalks Password Cracker | Test candidate passwords against the supplied hash |
| PDF reader | Open the protected PDF after password recovery |

## Procedure

### Step 1 — Obtain the encrypted PDF

The task identifies the locked training file as `My Locked PDF1.pdf` during the procedural walkthrough.

### Step 2 — Open the Hash Calculator

The Networkwalks Hash Calculator was opened in a web browser.

### Step 3 — Upload the locked PDF

The protected PDF was uploaded to the Hash Calculator. The tool produced a PDF hash beginning with `$pdf$...`.

### Step 4 — Copy the complete hash

The complete generated hash was copied, including the initial `$pdf$` portion.

### Step 5 — Open the Password Cracker

The Networkwalks Password Cracker was opened in a web browser.

### Step 6 — Submit the hash and start the attack

The extracted hash was pasted into the Password Cracker and the cracking process was started.

### Step 7 — Record the recovered password

The report records the recovered lab password as:

`password1`

### Step 8 — Enter the password into the PDF

The recovered password was entered into the locked PDF.

### Step 9 — Confirm successful access

The PDF opened successfully, completing the practical.

## Results

| Item | Result |
|---|---|
| PDF file | My Locked PDF2 |
| Hash extracted | Yes |
| Cracking status | Successful |
| Recovered password | `password1` |
| PDF access confirmed | Yes |
| Completion date | 24/09/2026 |

> **Note:** The source report displays only a partial/truncated representation of the extracted hash in its results table. This repository does not reconstruct or invent the missing hash characters.

## Evidence

Evidence pages extracted from the submitted report are available in [`../../evidence/module-2-networkwalks/`](../../evidence/module-2-networkwalks/).

## Discussion

The exercise demonstrates the relationship between a protected file, a password-derived hash, and password-recovery attempts. It also reinforces the distinction made in the source material between encryption and hashing and the importance of strong, unique passwords.

## Ethical Considerations

The practical is documented as an authorized cybersecurity training exercise. Password-cracking techniques should not be applied to third-party files, systems, accounts, or datasets without explicit authorization.

## Source

See the original report in [`WK_3FinaltaskReport.pdf`](WK_3FinaltaskReport.pdf).
