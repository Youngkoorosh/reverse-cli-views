# 🔄 Reverse CLI Views — Head & Tail Mastery

Welcome to a hands-on Linux shell challenge focused on mastering `head`, `tail`, and pipeline techniques for file and directory inspection. This exercise simulates a real-world scenario with large file structures and precise output requirements.

## 📦 Project Structure

```
quera/
├── content.txt
└── tmp/
    └── 2000+ files and directories
```

You're currently located inside the `quera` directory.

---

## 🧪 Tasks Overview

### 1️⃣ View from Line 2395 to End of `content.txt`
Use `tail` to extract everything from line 2395 onward.

### 2️⃣ List First 10 Entries in `tmp` with Human-Readable Sizes
Use `ls` with `-lh` and a pipeline to limit output to the first 10 lines.

### 3️⃣ View Lines 1151 to 1200 of `tmp` Listing
Use `ls -lh` piped through `head` and `tail` to isolate the desired range.

### 4️⃣ View First 120 Bytes of `content.txt`
Use `head` with byte-specific options to extract exactly 120 bytes.

---

## 🚫 Constraints

- Do **not** use `cd` or change directories.
- Use only `head`, `tail`, `ls`, and pipelines.
- Each command must be written on a single line.
- Output must match the format and range described.

---

## 📤 Submission

Submit your four commands in a single `.sh` file or paste them line-by-line.

---

## 🧠 Tip

Explore `man head`, `man tail`, and `man ls` for hidden gems. Precision matters.

Happy hacking! 🧪🐚
