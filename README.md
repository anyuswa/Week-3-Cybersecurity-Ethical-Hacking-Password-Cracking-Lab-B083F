# Week 3 Cybersecurity & Ethical Hacking — Password Cracking Lab

This repository contains the evidence and documentation for the Week 3 practical work covering:

1. **Project Module 1 — Password Cracking with John the Ripper (JTR) and Johnny**
2. **Project Module 2 — Password Cracking with Networkwalks Tools**

The work is documented as an **authorized cybersecurity training/lab exercise**. The repository is intended for portfolio, assessment, and GitHub documentation purposes.

## Repository Structure

```text
week3-password-cracking-networkwalks/
├── README.md
├── .gitignore
├── docs/
│   ├── WK_3FinaltaskReport.pdf
│   ├── module-1-jtr.md
│   └── module-2-networkwalks.md
├── evidence/
│   ├── module-1-jtr/
│   │   ├── page-02.png
│   │   ├── page-03.png
│   │   ├── page-04.png
│   │   ├── page-05.png
│   │   ├── page-06.png
│   │   └── page-07.png
│   └── module-2-networkwalks/
│       ├── page-10.png
│       ├── page-11.png
│       ├── page-12.png
│       ├── page-13.png
│       ├── page-14.png
│       ├── page-15.png
│       ├── page-16.png
│       └── page-17.png
└── notes/
    └── evidence-notes.md
```

## Learning Objectives

- Understand the relationship between protected files, password-derived hashes, and password recovery.
- Extract a PDF hash in a controlled lab environment.
- Load and process a hash using password-recovery tooling.
- Document evidence for each major stage of the workflow.
- Verify successful recovery by opening the protected training PDF.
- Apply ethical and authorization requirements to dual-use security tools.

## Module 1 — John the Ripper / Johnny

The documented workflow is:

1. Prepare John the Ripper and Johnny.
2. Configure Johnny to use `John.exe`.
3. Obtain the encrypted PDF hash.
4. Save the hash in `hash1.txt`.
5. Load the hash file into Johnny.
6. Start the password-cracking attack.
7. Use the recovered password to open the protected PDF.

The source report records all major stages as completed.

See [`docs/module-1-jtr.md`](docs/module-1-jtr.md).

## Module 2 — Networkwalks Tools

The documented workflow is:

1. Obtain the encrypted PDF.
2. Open the Networkwalks Hash Calculator.
3. Upload the protected PDF and extract the `$pdf$...` hash.
4. Copy the complete hash.
5. Open the Networkwalks Password Cracker.
6. Submit the hash and start the attack.
7. Record the recovered password.
8. Enter the recovered password into the PDF.
9. Confirm successful access.

The report records the cracking status as **Successful** and PDF access as **confirmed**.

See [`docs/module-2-networkwalks.md`](docs/module-2-networkwalks.md).

## Evidence

Screenshots extracted from the submitted report are stored under:

- `evidence/module-1-jtr/`
- `evidence/module-2-networkwalks/`

You can replace or supplement these with your own original screenshots if your assessor requires direct evidence from your own GitHub repository.

## Ethical Use

Password-cracking tools are dual-use security tools. This repository documents their use only in the context of an authorized training/lab exercise. Do not use the techniques or tools against files, accounts, systems, or datasets without explicit authorization.

## Source Report

The original submitted report is preserved at:

`docs/WK_3FinaltaskReport.pdf`

---

**Learner:** ASANDA LLOYD NYUSWA  
**Program / Batch:** B083F  
**Platform:** Windows PC  
**Completion date:** 24/09/2026
