# How to convert a TCP file to TDL

This guide walks through recovering readable TDL from a Tally `.tcp` file using [tcpdecompiler.in](https://tcpdecompiler.in).

## Before you start

- Keep a backup copy of your `.tcp` file.
- Make sure you own the file or have permission to work on it.
- Note the file size. Regular TCP files strictly below 5 KB may qualify for free Community recovery.

## Steps

### 1. Create an account
Sign up on the website with your email and password.

### 2. Upload the TCP file
Choose your `.tcp` file in the workspace. The server checks which layout the file uses (Regular, Inscribed V1 or Inscribed V2).

### 3. Review the price
Files that qualify for the free plan are processed without charge. For other files you see an exact price before anything is processed. A failed recovery is not charged.

### 4. Recover the source
The server reconstructs the TDL from the file.

### 5. Review and export
Read the result in the workspace, then copy it or download it as a `.tdl` or `.txt` file. You can optionally simplify aliases to make long formula chains easier to follow.

### 6. Reopen later
Successful recoveries are saved in your private library, and reopening a saved result does not cost again.

## Convert TCP to text

If you only want to read the logic, download the output as a **text file**. If you plan to load it back into Tally, download it as a **TDL file**.

## Common problems

| Problem | What to try |
|---------|-------------|
| File is not recognized | The layout may be unsupported. Contact the team for a manual review. |
| Output has unclear names | Obfuscated identifiers can survive recovery. Rename them as you learn what they do. |
| Output will not load in Tally | Some definitions may need adjustment. See the [after-recovery checklist](after-recovery-checklist.md). |

Need help? See the [FAQ](faq.md) or contact the team through the website.
