
<h1 align="center">👋 Hello, I'm generin0</h1>
<h3 align="center">Reverse Engineer & Low-Level Programming Enthusiast</h3>

<p align="center">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Assembly-red?style=for-the-badge&logo=assemblyscript&logoColor=white" alt="Assembly" />
  <img src="https://img.shields.io/badge/Reverse%20Engineering-green?style=for-the-badge" alt="Reverse Engineering" />
  <img src="https://img.shields.io/badge/Malware%20Analysis-darkred?style=for-the-badge" alt="Malware Analysis" />
</p>

---

## 🔬 About Me

I'm a passionate reverse engineer from **Ukraine** with deep interest in low-level programming, malware analysis, and system internals. I enjoy understanding how things work at the most fundamental level.

- 🔭 **Currently working on**: Automated analysis tools and shellcode development
- 🧠 **Learning**: Anti-analysis techniques and evasion methods
- 💻 **Daily drivers**: `C`, `Python`, `x86/x64 Assembly`, `Bash`
- 🛠️ **Tools**: IDA Pro, Ghidra, x64dbg, WinDbg, Radare2

**OS:** Ubuntu x86-64, Windows 11  
**Shell:** zsh  
**Location:** Odesa, Ukraine  
**Hobbies:** Gaming, Programming, Science, Music, Video editing

---

## 🛠️ Tech Stack

### **Reverse Engineering**
![IDA Pro](https://img.shields.io/badge/IDA_Pro-Pro?style=flat&logo=hex&logoColor=white&color=red)
![Ghidra](https://img.shields.io/badge/Ghidra-NSA?style=flat&logo=git&logoColor=white&color=green)
![x64dbg](https://img.shields.io/badge/x64dbg-Debugger?style=flat&color=blue)

### **Programming**
![C](https://img.shields.io/badge/C-Advanced-A8B9CC?style=flat&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-Intermediate-3776AB?style=flat&logo=python&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly-Beginner-red?style=flat&logo=assemblyscript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-Scripting-4EAA25?style=flat&logo=gnu-bash&logoColor=white)

---

## 🧠 Code Insight

```assembly
; Win64 MASM - Where art meets machine
.data
    msg db "In reverse engineering we trust",0

.code
main proc
    sub rsp, 40           ; Setup stack
    mov rcx, -11          ; STD_OUTPUT_HANDLE  
    call GetStdHandle     ; Windows API call
    ; The rest is in the disassembly...
    add rsp, 40
    ret
main endp
```
----------

## 🏆 Featured Projects

### 🔧 [Custom Shell](https://github.com/generin0/Shell)
A custom shell implementation in C demonstrating low-level system programming and process management.

### 🛡️ [PatchGuard Research](https://github.com/generin0/PatchGuard)
Deep dive into PE Patch Guard internals and security mechanisms.

### 🧩 [CrackMe Solutions](https://crackmes.one/user/genass3)
My solutions and write-ups for various reverse engineering challenges.

----------

## 🎯 Currently Exploring

```c

// Anti-analysis techniques
if (IsDebuggerPresent()) {
    // Time to get creative!
    EvadeDetection();
} else {
    // Continue normal execution
    ExecutePayload();
}
```
-   **Shellcode development** & obfuscation techniques
    
-   **Windows internals** & kernel-mode programming
    
-   **Automated malware analysis** pipelines
    
-   **Vulnerability research** & exploit development
    

----------

## 📫 Connect With Me

<p align="center">
  <a href="https://github.com/generin0" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://discord.com/users/genesis6393" target="_blank">
    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" />
  </a>
  <a href="mailto:dimas1234ssa@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<p align="center">
  <i>"The truth is in the binary."</i>
</p>
