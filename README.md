# Cybersecurity CTF Challenges

Welcome to my Cybersecurity CTF Challenge Repository. This repository is designed **solely for educational and research purposes**, providing a safe environment to practice and enhance your reverse engineering and cybersecurity skills. All provided challenges have been carefully developed to ensure they pose no risk when executed in a **controlled environment** (e.g., sandbox or virtual machine).

> ⚠️ **This is a work-in-progress (WIP) / draft project.**  
> Feedback, suggestions, and contributions are highly appreciated!

## Table of Contents
- [Overview](#overview)
- [Challenges](#challenges)
- [Usage Guidelines](#usage-guidelines)
- [Disclaimer](#disclaimer)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository contains a set of reverse engineering challenges, inspired by real-world adversary tradecraft. The goal is to help learners and researchers develop their technical skills through hands-on binary analysis and problem-solving.

Included challenges:
- `CTF_Vice.exe`
- `CTF_Phantom.exe`
- `CTF_Vidar.exe`
- `CTF_LockBit.exe`
- `CTF_Amos.exe`
- `CTF_Cyclix.exe`

## Challenges

Each executable presents a unique problem requiring reverse engineering, static/dynamic analysis, and understanding of software internals.

- **CTF_Vice.exe**
  - **Difficulty**: Moderate  
  - Objective: Develop a key generator that replicates the logic used internally. Reverse the algorithm and implement a working solution.

- **CTF_Phantom.exe**  
  - **Difficulty**: Hard  
  - Objective: Recover a hidden key and understand the underlying mechanism. This challenge emphasizes advanced static and dynamic analysis.

- **CTF_Vidar.exe** 
  - **Difficulty**: Moderate  
  - Objective: Perform reverse engineering to extract a hidden key and analyze the logic used to protect or obfuscate it.

- **CTF_LockBit.exe**  
  - **Difficulty**: Moderate  
  - Objective: Extract the embedded key by defeating basic anti-analysis or obfuscation routines.

- **CTF_Amos.exe**  
  - **Difficulty**: Moderate  
  - Objective: Identify and extract the hidden key through classic reverse engineering techniques, such as control-flow analysis and memory inspection.

- **CTF_Cyclix.exe** 
  - **Difficulty**: Easy  
  - Objective: Extract the embedded key using fundamental static or dynamic analysis techniques.

## Usage Guidelines

1. **Educational Purpose**  
   These challenges are intended strictly for educational use. Run them only in isolated environments (e.g., sandbox, VM) to avoid unintended interactions.

2. **Environment Setup**  
   - Use a virtual machine or sandboxed environment.
   - Recommended tools: Ghidra, IDA, x64dbg, Cutter, dnSpy, or Radare2.

3. **Documentation & Reporting**  
   - Document your analysis, approaches, and findings.
   - You're welcome to share insights, methodologies, and write-ups via issues or discussions.

4. **Collaboration**  
   Contributions—whether in the form of write-ups, enhancements, fixes, or new challenges—are welcome! Please submit a pull request or open an issue to get started.

## Disclaimer

This repository is provided **"as-is"**, strictly for educational and ethical purposes.  
The binaries do not contain malicious payloads and are safe to execute **only in a controlled lab setup**.  
The author assumes **no responsibility** for misuse or unintended consequences. Always ensure you operate within the bounds of local laws and run code only on systems where you have full authorization.

## Contributing

As this is a draft project, **all feedback and collaboration are welcome**. If you:
- Found a bug
- Have suggestions
- Want to submit a write-up
- Or just want to say hi

Feel free to reach out via issues, discussions, or pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
