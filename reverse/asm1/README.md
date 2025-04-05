# asm1

**Category**: Reverse Engineering  
**Points**: 100  
**Challenge Description**:  
We’re given a simple binary to reverse. It prints a message if the correct input is entered.

---

### My Thought Process

I opened the binary in Ghidra and looked at the `main` function. It compares our input with a hardcoded string using `strcmp`.

I used `strings` and `objdump` to analyze it quickly and confirmed the check value was `"secret_input"`.

---

### Tools Used

- Ghidra
- strings
- objdump

---

### Flag

Format: `picoCTF{...}`  
Flag is not shown to respect the challenge.
