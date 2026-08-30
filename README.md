<div align="center">
  <img src="https://img.shields.io/badge/MODX-LAB-38bdf8?style=for-the-badge&logoColor=white" alt="ModX Lab">
  
  <h1>🚀 Subway Surfers RVA Dumper</h1>
  
  <p><b>Advanced Client-Side IL2CPP Offset Extractor by Namespace, Class & Method</b></p>
  
  [![Live Demo](https://img.shields.io/badge/Live_Demo-Access_Tool-10b981?style=for-the-badge&logo=github)](https://modxlab00.github.io/Subway-Surfers-Offset-Finder/)
  [![Built With](https://img.shields.io/badge/Built_With-HTML5_|_CSS3_|_JS-0f172a?style=for-the-badge)](#)
</div>

<br>

Welcome to the **Subway Surfers RVA Dumper**, a premium utility designed for game modders and reverse engineers. This tool securely processes your `dump.cs` files locally within your browser to extract precise Relative Virtual Addresses (RVA) without risking offset collisions.

## ✨ Premium Features

* 🔒 **100% Client-Side Processing:** Built with Javascript `FileReader`. Your `dump.cs` file is processed entirely in your browser memory and never uploaded to any server.
* 🎯 **Hierarchical Precision Mapping:** Employs strict validation across `Namespace` ➔ `Class` ➔ `Method` to ensure pinpoint accuracy, ignoring duplicate method names in other classes.
* 💎 **Modern Dark Glassmorphism UI:** An immersive, hardware-accelerated user interface featuring glowing accents, deep ambient lighting, and smooth animations.
* 📦 **Instant Developer Export:** Automatically generates formatted `.txt` files containing everything you need for C++ / KittyMemory hooks (Mod Logic, Returns, Parameters, and RVAs).

## 🛠️ Integrated Mod Logic Targets

The extractor is pre-configured to locate offsets for the following core Subway Surfers features:

| Feature | Mod Logic Output |
| :--- | :--- |
| **CheckFrontalImpact** | `return false` (God Mode) |
| **CheckSideImpact** | `return false` (God Mode) |
| **Unlimited Jump** | `return 999` |
| **Custom Jump Height** | `return 35.0` |
| **Auto Revive** | `return true` |
| **Unlimited Coins** | `return 99999999` |
| **Free In-App Purchases** | `return false` |
| **0 Lane Change Duration**| `return 0.0` |

## 🚀 Usage Instructions

1. **Extract Game Data:** Use *Il2CppDumper* with the target `libil2cpp.so` and `global-metadata.dat` files from the Subway Surfers APK.
2. **Access Tool:** Navigate to the [Live RVA Dumper](https://modxlab00.github.io/Subway-Surfers-Offset-Finder/).
3. **Upload & Process:** Click the upload box, select your generated `dump.cs` file, and hit **PROCESS FILE**.
4. **Review & Download:** Review the beautifully formatted table. Click the **DOWNLOAD EXTRACTED FILE** button to save your ready-to-hook offsets text file.

---
<div align="center">
  <i>© 2026 ModX Lab. All Rights Reserved.</i>
</div>
