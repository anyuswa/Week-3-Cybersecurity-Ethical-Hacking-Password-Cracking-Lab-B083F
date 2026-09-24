# Week 3 — Password Cracking with John the Ripper & Networkwalks Tools

> **Cybersecurity / Ethical Hacking — Authorized Training Lab**

This repository contains the project evidence and written report for **Week 3 Project Modules 1 and 2**, covering controlled password-recovery exercises against supplied training PDFs.

## Project overview

The practical work documents two workflows:

1. **Module 1 — John the Ripper (JTR) + Johnny GUI**
   - Prepare John the Ripper and Johnny on Windows.
   - Configure Johnny to use `john.exe`.
   - Extract a PDF password hash.
   - Save the hash as `hash1.txt`.
   - Load the hash into Johnny and run the attack.
   - Verify access to the protected PDF.

2. **Module 2 — Networkwalks Tools**
   - Use the Networkwalks Hash Calculator to extract a PDF hash.
   - Submit the hash to the Networkwalks Password Cracker.
   - Record the recovered password.
   - Verify that the supplied protected PDF opens successfully.

The original report records completion of both practical workflows and includes screenshot evidence from the Windows environment. 

## Repository structure

```text
week-3-password-cracking-lab/
├── README.md
├── .gitignore
├── docs/
│   └── PROJECT_REPORT.md
├── evidence/
│   ├── evidence-01.*
│   ├── evidence-02.*
│   └── ...
└── assets/
    └── README.md
```

## Learning objectives

- Understand the relationship between protected files, hashes and password-recovery attempts.
- Configure a graphical interface for John the Ripper.
- Extract and handle a PDF hash in a controlled lab.
- Document a repeatable password-recovery workflow.
- Verify successful recovery by opening the supplied training PDF.
- Understand why simple or predictable passwords are vulnerable to systematic password testing. 
## Tools

| Tool / Resource | Purpose |
|---|---|
| John the Ripper | Password/hash cracking engine |
| Johnny GUI | Graphical interface for John the Ripper |
| Networkwalks Hash Calculator | PDF hash extraction |
| Networkwalks Password Cracker | Candidate-password testing |
| Text editor | Saving the extracted hash as `hash1.txt` |
| PDF reader | Verifying recovered access |

The report identifies John the Ripper and Johnny as the Module 1 tools and the Networkwalks Hash Calculator and Password Cracker as the Module 2 tools. 

## Results

### Module 1

The report records the following completed stages:

- JTR available
- Johnny configured with `john.exe`
- PDF hash extracted
- `hash1.txt` created
- Attack completed
- Protected PDF opened successfully fileciteturn0file0L87-L112

### Module 2

The report records:

- Locked PDF obtained
- Hash Calculator opened
- `$pdf$` hash extracted
- Complete hash copied
- Password Cracker opened
- Attack started
- Password recovered
- Recovered password entered into the PDF
- PDF opened successfully fileciteturn0file0L256-L280

## Evidence

The [`evidence/`](evidence/) directory contains the screenshots embedded in the original Word report. The screenshots document configuration, hash extraction, hash loading, attack execution and successful PDF access. For example, the screenshots on pages 3–6 show the Johnny configuration and cracking workflow, while pages 11–15 show the Networkwalks workflow and successful recovery. 

## Ethics and authorization

Password-cracking tools are dual-use security tools. This repository is intended for **authorized training, lab work and defensive security education only**. The original report explicitly states that the exercise targeted supplied training PDFs and was not intended to obtain unauthorized access to third-party information. fileciteturn0file0L116-L121

Do not apply these techniques to systems, accounts, files or datasets without explicit authorization. 

## External resources

- Openwall — John the Ripper: https://www.openwall.com/john/
- Openwall — Johnny: https://openwall.info/wiki/john/johnny
- Networkwalks Hash Calculator: https://networkwalks.com/hash-calculator/
- Networkwalks Password Cracker: https://networkwalks.com/password-cracker/

## Author / project metadata

- **Learner:** Asanda Lloyd Nyuswa
- **Program / Batch:** B083F
- **Platform:** Windows PC
- **Project:** W3-PM1 / Week 3 Project Modules 1–2
- **Completion date:** 24 September 2026


---


