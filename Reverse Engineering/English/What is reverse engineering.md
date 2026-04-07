# What is Reverse Engineering?

**Reverse engineering** (back engineering) is the process of examining a finished device or software to understand how it is designed and how it functions. While regular programming is like building a model using an instruction manual, reverse engineering is like taking a finished model apart to create that manual from scratch.

## Goals of the Process
1.  **Security Analysis:** Searching for vulnerabilities and hidden features (backdoors) in software.
2.  **Compatibility:** Making old software run on modern systems.
3.  **Code Recovery:** Understanding the product's logic if the original source code was lost.
4.  **Malware Analysis:** Studying how viruses and trojans work to create antivirus signatures.

## How it works in software
Since we don't have the source code, specialized tools are used:
*   **Disassemblers:** Turn ones and zeros back into readable (but complex) Assembly code.
*   **Decompilers:** Attempt to reconstruct code in a high-level language (like C++ or Java).
*   **Debuggers:** Allow you to run a program step-by-step and see what is happening in the computer's memory at any given moment.

## Ethical Considerations
Reverse engineering is legal for personal learning, bug hunting, or ensuring compatibility. However, using it to bypass protections (cracking) or steal intellectual property is a violation of the law.
