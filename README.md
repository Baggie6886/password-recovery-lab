# password-recovery-lab

# Private challenge materials and recovered credentials
*.pdf
*.hash
*.txt
*.pot
*.john
# Keep only intentionally curated evidence in screenshots
.DS_Store
Thumbs.db

MIT License

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.

A hands-on cybersecurity lab exploring password-protected PDF recovery using hash analysis, John the Ripper, and password-cracking tools in an authorized environment.
A hands-on cybersecurity learning exercise exploring password recovery for PDF files in an authorized lab environment. This repository documents the workflow, tools, observations, and lessons learned—not just the final result.


## Objectives
- Understand the relationship between a protected file, password verification, and hashes.
- Practice using a hash calculator and password-recovery tools in a controlled challenge.
- Learn where John the Ripper fits into a password-recovery workflow.
- Record evidence and reflect on the process.

## Tools used
- **John the Ripper** — password-recovery utility used during the challenge.
- **Hash Calculator** — used to calculate and inspect hash values.
- **Password-cracking tool** — used as part of the challenge workflow.

See [`tools/tools-used.md`](tools/tools-used.md) for notes.

## Lab workflow (high-level)
1. Work with the challenge PDF supplied for the lab.
2. Identify the file's protection and determine what hash or password-verification material the challenge makes available.
3. Calculate or extract the relevant hash using the lab's approved tooling.
4. Run the password-recovery process against the challenge data using the selected tool.
5. Verify the recovered password against the challenge file and record the outcome.
6. Capture evidence and document what was learned.

## Evidence
Screenshots from the exercise are included in [`screenshots/`](screenshots/). They are provided as learning evidence; challenge flags and sensitive details should be redacted before sharing publicly if the lab rules require it.


## Ethics and scope
This exercise was performed for learning in a controlled, authorized environment. Password recovery should only be attempted on files you own or have explicit permission to test. Do not use these techniques to access other people's files or data.


## Learning takeaway
Tools are useful, but understanding the workflow—file protection, hashes, tool selection, verification, and documentation—is what makes the exercise valuable.

# Methodology

This lab followed a controlled, authorized challenge workflow:


1. **Scope** — Confirm that the target PDF is provided for the exercise and is in scope.
2. **Inspect** — Identify the file and its protection context.
3. **Hash analysis** — Use the calculator/tooling supplied by the challenge to inspect relevant hash values.
4. **Recovery attempt** — Use the selected password-recovery tool on challenge data.
5. **Validation** — Verify the recovered credential by opening the original challenge PDF.
6. **Evidence and reporting** — Save screenshots, summarize the steps, and record lessons learned.


This is an overview for the authorized lab, not a general-purpose guide to accessing files without permission.

# Lab Report: PDF Password Recovery

## Summary
This exercise involved recovering the password to a protected PDF file within a cybersecurity training challenge. I used a hash calculator, John the Ripper, and a password-recovery/cracking tool as part of the workflow.

## Objective
Practice a file-password recovery workflow and build familiarity with hash analysis and password-recovery utilities.

## Tools
- John the Ripper
- Hash Calculator
- Password-recovery/cracking tool used in the training environment

## Process overview
1. Selected the protected PDF challenge file.
2. Examined the file and worked with the hash information available in the exercise.
3. Used the hash calculator to calculate/inspect hash values.
4. Applied the password-recovery tool(s) to the challenge material.
5. Tested the recovered password against the protected PDF and captured challenge completion evidence.

## Result
The challenge was completed successfully and the training environment displayed flag-capture confirmations. Screenshots are available in the `screenshots/` directory.

## Observations
- A hash is not the plaintext password; it is a value used in verification and may be the input to an offline recovery workflow in a challenge.
- Tool choice and understanding the input format are important.
- Successful recovery should be verified against the original challenge file.
- Documentation and screenshots help make practical work reproducible and reviewable.

## Limitations
This report records the learning workflow at a high level. It does not include sensitive challenge credentials or detailed cracking commands.


## Ethics
Only files that I own or am explicitly authorized to test should be used for password recovery.

# Lessons Learned

- Password recovery is a process, not simply guessing passwords.
- Hashes and plaintext passwords are different; understanding the role of the hash is essential.
- Tool input and file format matter. A tool must receive the type of data it expects.
- Recovery results should be validated against the original file.
- Keeping screenshots and a concise report turns an exercise into portfolio evidence.
- Cybersecurity tools should be used only within authorized scope.


## Next steps
- Review how PDF password protection and hash verification work at a conceptual level.
- Compare tool output and document the differences observed during the lab.
- Redact challenge tokens/flags if sharing evidence outside the training platform.

# Tools Used

## John the Ripper
A password auditing and recovery utility used in the challenge as part of the recovery workflow.

**Role in this lab:** password recovery attempt against challenge-provided material.

## Hash Calculator
A utility for calculating and examining cryptographic hash values.
**Role in this lab:** hash calculation/inspection during the exercise.

## Password-recovery tool
The challenge workflow also used a password-cracking interface/tool to attempt recovery.
**Role in this lab:** run the recovery attempt and observe the result.


> Tool descriptions are intentionally brief. Refer to each project's official documentation for full details and safe usage.

<img width="905" height="566" alt="john-the-ripper-challenge" src="https://github.com/user-attachments/assets/ad567e56-33c7-42fa-82a4-da7723182948" />
<img width="749" height="558" alt="hash-calculator-and-cracker" src="https://github.com/user-attachments/assets/6d107c11-635d-43a6-8361-de67ad50da61" />
<img width="432" height="531" alt="flag-capture-03" src="https://github.com/user-attachments/assets/b85bb5ad-6316-4c76-a6b7-c78988522367" />
<img width="491" height="556" alt="flag-capture-02" src="https://github.com/user-attachments/assets/a0865a8b-7b17-4f41-910d-d5eab29c4b87" />
<img width="493" height="570" alt="flag-capture-01" src="https://github.com/user-attachments/assets/98a98868-52b0-40bd-b4a5-d43581f04826" />
