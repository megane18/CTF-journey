# Safe opener

**Category**: Reverse Engineering  
**Points**: 100  
**Challenge Description**:  
The key to a digital safe has been lost, but there's a program that might help us retrieve it. Our ask is to figure out the correct password to unlock the safe. Once recovered, we format our answer as picoCTF{your_password}.

---

### My Thought Process

So, I was thinking of using Ghidra for this challenge, however I received a .java file. This means, I am working at the highest level. So, I needed a way to decode the encoded password.

💡 **Tip**: If you're using WSL, Mac, or Linux, the `base64 -d` command in terminal is super handy! Good luck!

---

### Tools Used

- Java source analysis
- Base64 decoding (via terminal)

---

### Flag

Format: `picoCTF{your_decoded_password}` 

I’ve excluded the actual flag here to respect the integrity of the challenge.

