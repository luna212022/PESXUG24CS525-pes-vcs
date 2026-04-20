# PES-VCS (Version Control System)

## Overview
PES-VCS is a simplified version control system implemented in C.  
It mimics core functionalities of Git such as object storage, staging, commits, and history tracking.

---

## Features

- Initialize repository (pes init)
- Add files to staging area (pes add)
- View staged files (pes status)
- Create commits (pes commit)
- View commit history (pes log)

---

## Project Structure

.pes/
├── objects/        # Stores blobs, trees, commits  
├── refs/           # Branch references  
├── HEAD            # Points to current branch  
└── index           # Staging area  

---

## Phases Implemented

Phase 1:
- Blob object creation and storage

Phase 2:
- Tree structure and serialization

Phase 3:
- Index (staging area) implementation

Phase 4:
- Commit creation and history traversal

---

## How to Run

Compile:
make pes

Initialize repository:
./pes init

Add files:
./pes add file1.txt

Check status:
./pes status

Commit changes:
./pes commit -m "message"

View log:
./pes log

---

## Concepts Used

- Hashing for object identification  
- File system-based storage  
- Serialization and deserialization  
- Tree and graph traversal  

---

## Limitations

- No branching support (basic version)  
- No merge functionality  
- No advanced conflict resolution  

---

## Author

Name: YOUR NAME  
SRN: YOUR SRN  

---

## Conclusion

This project demonstrates the core working principles of a version control system and provides understanding of how tools like Git manage data internally.
