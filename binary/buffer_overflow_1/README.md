# buffer_overflow_1

**Category**: Binary Exploitation  
**Points**: 200  
**Challenge Description**:  
We’re given a binary vulnerable to buffer overflow. Goal is to overwrite return address and get shell.

---

### My Thought Process

Used `gdb` to inspect buffer size and crafted payload with padding + new return address.

---

### Tools Used

- gdb
- pwntools

---

### Flag

Format: `picoCTF{...}`  
Flag is not shown to respect the challenge.