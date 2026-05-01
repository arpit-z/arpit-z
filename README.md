# Hi there 👋 My name is Arpit and I'm using this Git repository to share my DevOps journey

I'm using my homelab as a playground to learn DevOps. Here are some projects I've completed or am currently working on:

## Linux Fundamentals - Arch Linux Install
**What I did:** I performed a fresh manual installation of Arch Linux from scratch to learn Linux fundamentals. Highlights:
- GRUB bootloader — configured to boot multiple kernels (linux and linux-lts) to ensure a fallback working system.
- BTRFS on LUKS — root and home on a LUKS-encrypted partition with BTRFS snapshots and rollbacks. Rolling back the kernel along with root‑filesystem packages took the longest to figure out.
- Secure Boot and TPM unlocking — implemented Secure Boot (created keys and signed the kernel) and configured the TPM2 chip to automatically unlock the LUKS partition if Secure Boot succeeds.

**What I learned:** It took me about a week to get a working Arch system 😀. I learned:
- Linux boot process
- Filesystems: EXT4, BTRFS, ZFS
- Linux file permissions
- systemd
- Package management
- Debugging via logs
- Basic Bash scripting

**Current State:**
After running Arch Linux for a month I switched to Fedora — I was spending more time fixing my workstation than using it to build my homelab; my Fedora workstation also has a fallback kernel and I take a BTRFS snapshot before every major update. Fedora just works.
<!--
**arpit-z/arpit-z** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
