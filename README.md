# Mikasa Kernel - POCO M3 / Redmi 9T (Chime/Juice)

**Mikasa Kernel** is a custom kernel specifically designed for Qualcomm Snapdragon 662 devices under the **Chime** (POCO M3) and **Juice** (Redmi 9T / Redmi 9 Power / Redmi Note 9 4G) codenames. This kernel focuses on stability, daily performance optimization, and efficient power management.

---

## 🛠️ Build Details & Specifications

| Component | Specification |
| --- | --- |
| **Architecture** | ARM64 |
| **Target Devices** | POCO M3 (`citrus`), Redmi 9T (`lime`), Juice |
| **Chipset** | Qualcomm Snapdragon 662 (SM6115) |
| **Compiler** | Optimized using the latest Clang/LLVM toolchain |

---

## 📥 How to Compile (Quick Build)

If you want to compile the kernel manually using a build script or within a Linux/Codespaces environment:

1. **Clone the Repository:**
```bash
git clone git@github.com:Notednop/Mikasa_kernel_chime.git
cd Mikasa_kernel_chime

```


2. **Setup Toolchain & Environment:**
Ensure you have exported the compiler path (such as Clang or GCC) into your terminal environment.
3. **Start the Build:**
```bash
make O=out mikasa_defconfig
make O=out -j$(nproc)
or -> sudo bash compile.sh

```



---

## 🤝 Contribution & Credits

Contributions in the form of bug reports, pull requests, or optimization suggestions are always welcome. Special thanks to the Android community and kernel developers for the base source and patches used in this project.

---

> **Disclaimer:** Flashing a custom kernel always carries risks. Make sure to back up your boot partitions before installation. This project is provided "as-is" without any warranties.
