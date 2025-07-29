# Find Duplicate Images

[![🔥 Follow my GitHub](https://img.shields.io/badge/👉🏼-GitHub-white)](https://www.github.com/fcardan)
[![🔥 Follow my Linkedin](https://img.shields.io/badge/👉🏼-Linkedin-blue)](https://www.linkedin.com/in/fcardan)
[![⭐ pt-br](https://img.shields.io/badge/👉🏼-PtBr-green)](https://github.com/fcardan/find-duplicate-images/blob/main/README-ptbr.md)
[![⭐ Star](https://img.shields.io/github/stars/fcardan/find-duplicate-images)](https://github.com/fcardan/find-duplicate-images)

A lightweight Python script that identifies duplicate images in a directory by comparing MD5 hashes. Efficiently detects duplicates across common image formats (JPG, PNG, GIF, etc.) using file content hashing, ideal for organizing large media libraries

---

## Table of Contents  
- [Overview](#overview)  
- [Problem Solved](#problem-solved)  
- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Installation and Usage](#installation-and-usage)  
- [Generated Output](#generated-output)  
- [Workflow](#workflow)  
- [Thanks for Checking It Out](#thanks-for-checking-it-out)  
- [License](#license)

---

## Overview  
Python script identifies duplicate images in specified folder using MD5 hashing  
Compares file contents rather than filenames/sizes  
Provides interactive CLI for safe deletion of duplicates  

---

## Problem Solved  
1. **Storage waste** → Finds identical images occupying unnecessary space  
2. **Manual verification** → Automates content-based comparison  
3. **Accidental duplicates** → Detects copies across different folders/names  
4. **Unsafe deletion** → Preserves original file while removing copies

---

## Features  
| Feature | Functionality |  
|---------|---------------|  
| **Content Hashing** | MD5 hash comparison of image binaries |  
| **Format Support** | Handles JPG/PNG/GIF/BMP/WebP/TIFF |  
| **Safe Deletion** | Keeps first occurrence in each duplicate group |  
| **Verbose Mode** | Detailed processing logs |  
| **Recursive Scan** | Checks all subdirectories automatically |  
| **Error Handling** | Skips corrupt/unreadable files |    

---

## Tech Stack  
```plaintext
Core Language: Python 3.8+  
Libraries:  
- os (file system operations)  
- hashlib (MD5 hashing)  
- collections.defaultdict (group management)
```
