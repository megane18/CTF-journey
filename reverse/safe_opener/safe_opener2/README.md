# Safe Opener 2

**Category**: Reverse Engineering  
**Points**: Unknown  
**Challenge Description**:  
We're given a `.class` file that supposedly checks a password and opens a safe. Our task is to figure out the correct input (the flag) by reverse engineering the logic in the binary — this time, without being given the original Java source file.

---

### My Thought Process

I opened the `.class` file, which launched IntelliJ. I noticed it automatically decompiled the bytecode using FernFlower, which gave me Java-like source code. From there, I spotted the usage of `Base64.getEncoder()` and the presence of a string that looked like the final encoded key.

Rather than decoding anything manually, I could see the password logic directly — and the flag itself.

This was my first time realizing **decompilation can happen seamlessly in IDEs** like IntelliJ, which is both helpful and a great intro to deeper reverse engineering concepts.

---

### Tools Used

- IntelliJ (automatic FernFlower decompilation)
- No manual decoding needed — the flag was revealed in the decompiled logic.

---

### Flag
Format: `picoCTF{your_decoded_password}` 


The actual flag is not included to respect the integrity of the challenge.

