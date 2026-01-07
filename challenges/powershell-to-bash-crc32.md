# Challenge 4 – Convert powershellscript to bash

### Background

This challenge focuses on cross-platform scripting and AI-assisted development. You will convert a PowerShell script that calculates the CRC32 checksum of a file into an equivalent Bash script, without using built-in CRC utilities. The goal is to leverage GitHub Copilot to assist in both script creation and troubleshooting, ensuring both scripts produce the correct checksum for a given file.

### Objective

Create a PowerShell script and a Bash script that both calculate the CRC32 checksum for a given file (e.g., azure-overview.png), using GitHub Copilot for assistance. Ensure both scripts return the correct checksum (EBAFCEAD) and do not use built-in CRC utilities. Practice using Copilot to generate, debug, and refine your code across platforms.

## 1. Setup Your Development Environment

### Setup vscode with powershell extension:

- use Visual Studio Code (with Copilot enabled).
- install the powershell extension
- if on windows, make sure to have a running WSL subsystem. in case you need to install, follow the instructions from https://learn.microsoft.com/en-us/windows/wsl/install

## 2. If a folder does not exist for this Challenge, create one

e.g. crc32-conversion

## 3. Create new .ps1 file

e.g. `start.ps1`

## 4. let copilot create our starting point

- Open the file and start Copilot with *Ctrl+I*
- please choose as AI model GPT 4o
- Ask Copilot to create a Powershell function which calculates the CRC32 checksum for a given file (input parameter is the path to the file)
- The checksum has to be returned as a String
- Start the Script

## 6. Verify the Checksum

- Once the script runs successfully on `azure-overview.png`, you should see the correct CRC32 checksum: EBAFCEAD

## 7. Adjust the Model if Results Differ
- If you get incorrect results, switch to “o1 (preview)” if available.
- Let Copilot correct any errors in your script or logic.

## 8. switch back to GPT 4o
please change the used model back to GPT 4o

## 9. Bash Based Implementation

- Create a new Bash file (`start.sh`)
- Ask Copilot to convert your Script into Bash
- Attach the `start.ps1` file with "Attach Context" to Copilot
- Run Copilot
- dont use crc32 command or cksum, it would work ), but defy the purpose of the exercise
- In order to run this, in case you're running on Windows, please make sure you have a working WSL subsystem.
- Set execute permissions for the Bash script:
  ```bash
  chmod +x <path to crc32-conversion directory>/start.sh
  ```
- Run the script:
  ```bash
  <path to crc32-conversion directory>/start.sh
  ```
## 10. Verify the Checksum

- Once the script runs successfully on `azure-overview.png`, you should see the correct CRC32 checksum: EBAFCEAD

## 11. Adjust the Model if Results Differ
- If you get incorrect results, switch to “o1 (preview)” if available.
- Let Copilot correct any errors in your script or logic.

