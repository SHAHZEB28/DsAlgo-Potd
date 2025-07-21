# DsAlgo-POTD

> A curated repository of "Problem of the Day" (POTD) solutions covering various data structures and algorithms.

![GitHub Repo Size](https://img.shields.io/github/repo-size/SHAHZEB28/DsAlgo-Potd) ![GitHub Language Count](https://img.shields.io/github/languages/count/SHAHZEB28/DsAlgo-Potd) ![Last Commit](https://img.shields.io/github/last-commit/SHAHZEB28/DsAlgo-Potd)

---

## 📝 Table of Contents

* [About](#about)
* [Repository Structure](#repository-structure)
* [Getting Started](#getting-started)
* [Folder & File Conventions](#folder--file-conventions)
* [Contributing](#contributing)
* [License](#license)

---

## 📖 About

This repository hosts daily algorithmic challenges (POTD) solved in C++. Each solution is organized into folders corresponding to different data structures or algorithms.

Whether you’re preparing for interviews, brushing up on DSA topics, or simply practicing coding, you’ll find clear, commented implementations here.

---

## 📂 Repository Structure

```
DsAlgo-Potd/
├── TRIE/
│   ├── DeleteDuplicateFoldersinSystem.cpp  # POTD solution for deleting duplicates in a file system
│   └── ImplementTrieII.cpp                # Trie insertion/search implementation
├── Queue1/
│   └── ...
├── Recursion1/
│   └── ...
└── README.md                               # This file
```

* **TRIE/**: Problems and solutions related to trie (prefix tree) data structure.
* **Queue1/**: Queue-based problems.
* **RecursionX/**: Recursive algorithm challenges.
* *...and so on.*

> *Note: New folders are added as you solve problems in different categories.*

---

## 🚀 Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/SHAHZEB28/DsAlgo-Potd.git
   cd DsAlgo-Potd
   ```

2. **Compile and run**
   Each solution is a standalone C++ file. For example:

   ```bash
   g++ TRIE/DeleteDuplicateFoldersinSystem.cpp -std=c++17 -O2 -o delete_dup
   ./delete_dup
   ```

3. **Explore other solutions**
   Navigate to different folders and compile/run their respective solutions.

---

## 📐 Folder & File Conventions

* **Folder names**: Match the data structure or algorithm category (e.g., `TRIE`, `Queue1`, `Recursion2`).
* **File names**: Use `CamelCase` describing the problem (e.g., `DeleteDuplicateFoldersinSystem.cpp`).
* **Coding style**:

  * Use C++17 standard.
  * Add comments explaining the approach and complexity.
  * Keep functions modular and reusable.

---

## 🤝 Contributing

1. **Fork** the repository and create your own branch:

   ```bash
   git checkout -b feat/<problem-name>
   ```
2. **Add** your solution:

   * Create a new folder if category doesn’t exist (e.g., `Graph1/`).
   * Add your `ProblemName.cpp` file.
3. **Commit** your changes:

   ```bash
   git add .
   git commit -m "Add <ProblemName> solution"
   ```
4. **Push** to your fork:

   ```bash
   git push origin feat/<problem-name>
   ```
5. Open a **Pull Request** and describe your solution.

I’ll review and merge it!

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
