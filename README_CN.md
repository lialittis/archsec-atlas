```
 ▗▄▖ ▗▄▄▖  ▗▄▄▖▗▖ ▗▖ ▗▄▄▖▗▄▄▄▖ ▗▄▄▖     ▗▄▖▗▄▄▄▖▗▖    ▗▄▖  ▗▄▄▖
▐▌ ▐▌▐▌ ▐▌▐▌   ▐▌ ▐▌▐▌   ▐▌   ▐▌       ▐▌ ▐▌ █  ▐▌   ▐▌ ▐▌▐▌   
▐▛▀▜▌▐▛▀▚▖▐▌   ▐▛▀▜▌ ▝▀▚▖▐▛▀▀▘▐▌       ▐▛▀▜▌ █  ▐▌   ▐▛▀▜▌ ▝▀▚▖
▐▌ ▐▌▐▌ ▐▌▝▚▄▄▖▐▌ ▐▌▗▄▄▞▘▐▙▄▄▖▝▚▄▄▖    ▐▌ ▐▌ █  ▐▙▄▄▖▐▌ ▐▌▗▄▄▞▘
                                                               
.- .-. -.-. .... ... . -.-.    .- - .-.. .- ... 
```
# **ArchSec Atlas**

*A Personal Map of Mastery in Systems & Security*

---

## Overview

**ArchSec Atlas** 是我为自己设计的 **系统安全能力进化框架**。
它不是一个单独的技术项目， 而是一个结构化、 可持续扩展的 **学习路线图 + 实验集合 + 知识积累容器**。

Atlas（地图）的隐喻：

* 不是线性的课程
* 而是不断探索、 扩张、 填补未知区域的过程
* 它随时间成长， 成为我对系统安全世界的私人理解

本 Atlas 将作为五大方向的长期实践的坚持和总结：

1. Reverse Engineering + CTF + Bug Bounty
2. Operating Systems
3. Safe Programming Languages & Compilers (Rust, OCaml, LLVM)
4. LLM × System Security
5. Heterogeneous Architecture & Security (GPU/NPU)

---

## **Philosophy**

ArchSec Atlas 基于以下理念构建：

### **1. Learn by Practice**

每个方向都依赖可运行的 labs、 small projects、 experiments。

### **2. Build a Personal Worldview**

不是为了考试， 也不是固定课程， 而是形成
**架构 → 编译器 → 内核 → 二进制 → 漏洞**
贯通的系统安全观。

### **3. Keep It Modular**

每个方向都有独立 repo， Atlas 充当“中心导航节点”。

### **4. Continuous Evolution**

每周有更新， 每月有复盘， Atlas 会不断重构和生长。

---

# **Repository Structure**

```
archsec-atlas/
  README.md           ← 本文件
  roadmap/            ← 长期&短期路线图
  weekly-log/         ← 每周总结
  directions/         ← 五大方向导航文档
    reverse.md
    os.md
    compilers.md
    llm-security.md
    hetero.md
```

---

# **Five Directions (with sub-repositories)**

以下子链接是你未来会填写的 GitHub repos。
现在先占位， 等你创建好对应 labs 仓库再添加。

---

## 1. **Reverse Engineering + CTF + Bug Bounty**

> 逆向、 Pwn、 二进制漏洞、 真实挖洞
> 指向实际练习： Writeups、 ROP Lab、 Heap Lab、 Crackme、 Bug Bounty 报告等。

**Sub-repos:**

* 🔗 `reverse-labs`
* 🔗 `pwn-labs`
* 🔗 `ctf-writeups`

**Atlas document:**
`directions/reverse.md`

---

## 2. **Operating Systems**

> 从 xv6、 Linux 内核， 到内存管理、 调度器、 系统调用与安全机制。

**Sub-repos:**

* 🔗 `os-labs`
* 🔗 `kernel-labs`
* 🔗 `xv6-playground`

**Atlas document:**
`directions/os.md`

---

## 3. **Safe Programming Languages & Compilers**

> Rust（所有权/Unsafe）、 OCaml（parser/AST）、 LLVM（IR/Pass/Sanitizer）

**Sub-repos:**

* 🔗 `compiler-labs`
* 🔗 `rust-unsafe-labs`
* 🔗 `llvm-pass-labs`

**Atlas document:**
`directions/compilers.md`

---

## 4. **LLM × System Security**

> LLM 攻击与防御、 red-teaming、 AI-assisted RE、 自动化 static analysis

**Sub-repos:**

* 🔗 `llm-security-labs`
* 🔗 `llm-assisted-re`
* 🔗 `jailbreak-labs`

**Atlas document:**
`directions/llm-security.md`

---

## 5. **Heterogeneous Architecture & Security (GPU/NPU)**

> CUDA GPU 安全、 NPU 内存模型、 IOCTL、 加速器漏洞面

**Sub-repos:**

* 🔗 `hetero-security-labs`
* 🔗 `gpu-memory-labs`
* 🔗 `npu-security-labs`

**Atlas document:**
`directions/hetero.md`

---

# **Roadmap**

---

# **Weekly Log Template**

放在 `weekly-log/YYYY-WW.md`：

```
# Week XX — ArchSec Atlas Log

## 1. What I Practiced This Week
- 
- 

## 2. What I Learned
- 
- 

## 3. Experiments / Labs Completed
- 
- 

## 4. Problems / Bugs / Confusions
- 
- 

## 5. Next Week Plan
- 
- 
```

---

# How to Use ArchSec Atlas

1. **每个方向只有实验， 不读书空想**
   代码 > 文档 > 视频。

2. **最小单元学习法**
   每天一个 lab， 周期 1–3 小时。

3. **写日志与复盘**
   记录成长轨迹， Atlas 就会不断扩张。

4. **定期重构自己的路线图**
   兴趣、 能力、 目标都会改变， Atlas 也应该跟着进化。

# ⚖ License

For personal learning only (MIT / Unlicense recommended).
