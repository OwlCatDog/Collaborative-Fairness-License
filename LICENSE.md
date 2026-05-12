### Cooperative Fairness License (CFL) 1.0

Copyright (C) [Year] [Name]

#### Definitions
- **"Work"** means the copyrighted source code, object code, documentation, and related files accompanying this license.
- **"You"** means the individual or legal entity exercising permissions granted by this license.

#### 1. Core License
Provided you comply with Sections 2 and 3 of this license, you are permitted to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Work for any purpose.

#### 2. Unmodified Distribution Restriction

If you distribute copies of the Work (in source or executable form) **without adding any substantial new features or content**, you **may not** charge recipients a fee directly for such distribution.

**Exception:** You may charge a reasonable fee solely to cover the cost of physical media (e.g., blank CDs, USB drives) or network bandwidth.

**Determining Violations:**

- **"Unmodified" – Source Code:** The SHA-256 hash of the source code you distribute must be **identical** to the official source version provided by the original author.

- **"Unmodified" – Executables/Binaries:** The executable you distribute must satisfy one of the following:
    - (a) **Byte-for-byte identical** (SHA-256 hash matches) to the official binary version released by the original author; or
    - (b) **Built directly from the "unmodified" source code** above, using a standard, publicly documented build process, without any modifications to compiler flags, optimization levels, or embedded metadata that would change runtime behavior.

- **Trivial Changes (not considered "Modified"):** The following changes do **not** constitute "modification" for the purposes of this clause:
    - Line-ending conversions (LF to CRLF or vice versa)
    - Removal or addition of comments/whitespace that does not change executable behavior
    - Repackaging into different archive formats (.zip vs .tar.gz vs .7z)
    - Changes resulting from standard package manager processes (e.g., lockfile differences from `npm install`), provided no source logic is altered

- **"Substantial New Feature"** means a change that affects more than **6%** of the Work's total lines of code, as measured by `cloc` or a similar recognized tool. Changes limited to build scripts, configuration files, or dependency version updates, unless they alter runtime behavior, do not count toward this 6%.

#### 3. Prohibition of Harmful Modifications
You may not modify the Work or merge it with other code to introduce any objectively defined harmful functionality into the Work, including but not limited to the following examples:

1.  **Backdoors:** Functionality intentionally allowing unauthorized parties to bypass authentication or encryption protections.
2.  **Ransom Logic:** Functionality designed to disable, lock, or damage a user's system or data unless a ransom is paid.
3.  **Data Theft:** Functionality that transmits a user's personally identifiable information (PII) or sensitive data to a third party without the user's explicit, informed, separate consent (a click-through "I Accept").
4.  **Resource Abuse:** Functionality that uses a user's computing resources for cryptocurrency mining, DDoS attacks, or similar high-intensity tasks without the user's explicit request.

**Consequence of Violation:** Introducing any of the above functionality automatically and immediately terminates all rights granted to you under this license. You lose all rights to distribute or use the Work.

#### 4. Contributor Reciprocity Terms

**4.1 Source Code Publicity Exemption**

If you **publicly release** the **entire source code** of your modified version or related services (including all frontend, backend, database scripts, configuration files, but excluding purely local environment configuration files such as .env.local or files containing sensitive credentials) under an **OSI-approved open source license** (such as GPL, MIT, Apache 2.0) or this license (CFL), and make it freely accessible for anyone to view, use, modify, and distribute, then **all obligations under this Section 4 are automatically waived**.

If you stop publicly releasing the source code (e.g., by making the repository private), the waiver terminates immediately, and you will have **30 days** to either re-publicize the code or comply with the terms below.

**4.2 For-Profit Obligations**

If you **do not meet the exemption conditions in 4.1**, and by modifying the Work or developing services related to the Work (SaaS, hosted services, etc.), you obtain **net income exceeding $10,000 USD** (or equivalent in other currencies) over any consecutive 12 calendar months, you must **choose one** of the following two actions:

- **Option 1 – Provide Attribution:** Acknowledge the original author of the Work in a prominent location of your service (e.g., an "About" page).

- **Option 2 – Perform a single "Act of Love"**, such as any one of the following:
    (a) Submit at least one accepted bug fix or feature patch to the original author's project;
    (b) Write a technical blog post or documentation tutorial of at least 500 words for the original author's project;
    (c) Donate $100 USD to any organization that:
        - Is a recognized open source foundation (e.g., Apache Foundation, Linux Foundation, Software Freedom Conservancy, Open Source Initiative); or
        - Holds valid charitable/public benefit organization status at the time of donation (e.g., 501(c)(3) in the US, legal charity registration in China); or
        - Is a clear public domain project (e.g., Wikipedia, Internet Archive)

(Providing a donation receipt constitutes fulfillment of this obligation.)

#### 5. Disclaimer of Warranty and Limitation of Liability
THE WORK IS PROVIDED "AS IS", WITHOUT ANY WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE. IN NO EVENT SHALL THE ORIGINAL AUTHOR OR COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY, WHETHER IN CONTRACT, TORT, OR OTHERWISE, ARISING FROM THE USE OF THE WORK.

#### 6. Termination of Terms
If you violate Sections 2, 3, or 4 of this license, your rights granted hereunder automatically terminate. However, if you remedy the violation within 30 days of receiving written notice, your rights may be reinstated.

#### 7. Legal Effect Severability
If any part of this license is held unenforceable by a court of competent jurisdiction, the remaining parts remain in full force and effect. The unenforceable provision shall be deemed modified to the minimum extent necessary to make it enforceable while most closely reflecting the original intent; if such modification is impossible, the provision shall be deleted.