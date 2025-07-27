# 🧮 Calculator Project – Assembly (Shared)

👥 Shared with ALI CS Club

---

This is the **shared Assembly calculator repository** for ALI CS Club members.  
It focuses on implementing a terminal-based calculator using low-level x86 or x86_64 Assembly language.  
Due to the nature of Assembly, there is **no GUI version** planned — only CLI.

---

## 📁 Project Structure

```
calculator-asm-shared/
└── cli/
    └── calculator.asm         # CLI version – assemble and run with NASM + LD
```

---

## 🚀 How to Run

> ⚠️ Requires `nasm` and `ld` (Linux tools for assembling and linking)

```bash
cd cli
nasm -f elf64 calculator.asm -o calculator.o
ld calculator.o -o calculator
./calculator
```

---

## 🤝 Contribution Guidelines

- If you're working **independently**, please **fork** this repo or create a new **branch**, and submit a **pull request** when your work is ready to merge.
- If you're working **together with a club member** (e.g., in a meeting), only **one person should edit and push at a time** to avoid conflicts.
- Keep the Assembly code clean, commented, and focused on clarity and logic.

---

## 🧠 Purpose

This project helps reinforce:

- Deep understanding of registers, memory addressing, and arithmetic at the machine level
- Procedural flow control with jumps, conditionals, and stack operations
- Appreciation for how higher-level language features map to CPU instructions


The old-school way!
