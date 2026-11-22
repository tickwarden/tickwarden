<div align="center">

# 👋 Hi, I'm Legends11! / Merhaba, ben Legends11!

**Minecraft Fabric Mod Developer** | Modular Systems · GUI Frameworks · Storage-Driven Architecture  
**Minecraft Fabric Mod Geliştiricisi** | Modüler Sistemler · GUI Çerçeveleri · Depolama Tabanlı Mimari

![Profile Views](https://komarev.com/ghpvc/?username=tickwarden&color=blueviolet&style=flat-square&label=Profile+Views)

> **"Datapacks have limits. Fabric mods don't."**  
> **"Datapack'lerin sınırları var. Fabric mod'ların yok."**

</div>

---

## ⚡ Why Fabric? / Neden Fabric?

### 🚫 The Problem with Datapacks / Datapack'lerin Sorunu

**EN:** Datapacks are great for small projects — but they hit hard ceilings: no custom items with real behavior, no deep game loop control, no reliable networking, and format drift between MC versions.

**TR:** Datapack'ler küçük projeler için iyi — ama duvarla çarpışıyorsunuz: gerçek davranışlı özel item yok, derin oyun döngüsü kontrolü yok, güvenilir networking yok ve MC sürümleri arasında format kayması var.

| Feature / Özellik | Datapack | Fabric Mod |
|---|---|---|
| **Custom Item Behavior / Özel Item Davranışı** | ❌ Limited | ✅ Full control |
| **Mixins (Vanilla Injection)** | ❌ None | ✅ Full ASM |
| **Networking (C↔S Packets)** | ❌ None | ✅ Native |
| **Version Portability / Sürüm Taşınabilirliği** | 🔴 Breaks often | 🟢 Loom handles it |
| **GitHub CI/CD** | ✅ Text files | ✅ Gradle + Loom |
| **Performance (TPS)** | 🟡 Command overhead | 🟢 Native Java |
| **Dependency Management / Bağımlılık Yönetimi** | ❌ Manual | ✅ Gradle |
| **API Surface / API Yüzeyi** | 🔴 Commands only | 🟢 Full Java + FAPI |

### ✅ Fabric Advantages / Fabric Avantajları

- ✅ **Mixins** — Inject directly into vanilla classes / Vanilla sınıflara direkt inject
- ✅ **Full Java** — No mcfunction limitations / mcfunction sınırları yok
- ✅ **Fabric API** — Events, networking, registries out of the box / Hazır event, networking, registry
- ✅ **Loom** — Remapping, multi-version support / Remapping, çok sürümlü destek
- ✅ **Proper dependency graph** — Gradle, JARs, MavenCentral / Gerçek bağımlılık grafiği
- ✅ **GitHub Actions CI** — Build, test, release in one pipeline / Tek pipeline'da build, test, release

---

## 🎯 About Me / Hakkımda

**EN:** I build Minecraft Fabric mods targeting MC 1.21.x under the [runtoolkit](https://github.com/runtoolkit) and [ToolkitMC](https://github.com/ToolkitMC) GitHub organizations. My focus is on GUI frameworks, datapack-to-mod ports, and modular server-side tooling.

**TR:** [runtoolkit](https://github.com/runtoolkit) ve [ToolkitMC](https://github.com/ToolkitMC) GitHub organizasyonları altında MC 1.21.x hedefli Fabric modlar geliştiriyorum. Odak noktam GUI çerçeveleri, datapack-to-mod portları ve modüler sunucu tarafı araçlar.

- 🧩 **Modular Architecture / Modüler Mimari** — Clean, composable mod systems
- ⚡ **Performance First / Önce Performans** — Native Java, minimal overhead
- 🔐 **Security Focused / Güvenlik Odaklı** — No `java.awt.Desktop`, no HTTP abuse
- 📚 **MIT Licensed / MIT Lisanslı** — Open source, community-friendly
- 🇹🇷 **Turkish Developer / Türk Geliştirici** — Supporting the local Minecraft community

---

## 🚀 Featured Projects / Öne Çıkan Projeler

### 🎨 [ToolkitMC/guiAPI](https://github.com/ToolkitMC/guiAPI)
> **EN:** Datapack-driven chest GUI system for MC 1.21.x — action types, cooldowns, addon mods  
> **TR:** MC 1.21.x için datapack güdümlü sandık GUI sistemi — action tipleri, cooldown'lar, addon modlar  
> ![Stars](https://img.shields.io/github/stars/ToolkitMC/guiAPI?style=flat-square&color=yellow) ![Lang](https://img.shields.io/github/languages/top/ToolkitMC/guiAPI?style=flat-square)

### 📦 [runtoolkit/dataLib-FabricMod](https://github.com/runtoolkit/dataLib-FabricMod)
> **EN:** Core library mod — command handlers, permission system, scheduler, fiber system  
> **TR:** Çekirdek kütüphane modu — komut işleyiciler, izin sistemi, zamanlayıcı, fiber sistemi  
> ![Stars](https://img.shields.io/github/stars/runtoolkit/dataLib-FabricMod?style=flat-square&color=yellow) ![Lang](https://img.shields.io/github/languages/top/runtoolkit/dataLib-FabricMod?style=flat-square)
---

## 💻 Tech Stack / Teknoloji Yığını

<div align="center">

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Fabric](https://img.shields.io/badge/Fabric_Loader-DBD0B4?style=for-the-badge&logo=curseforge&logoColor=black)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)
![Minecraft](https://img.shields.io/badge/Minecraft-1.21.x-62B47A?style=for-the-badge&logo=minecraft&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</div>

**EN:** Languages: Java 21, JSON, Gradle Groovy/Kotlin DSL  
**TR:** Diller: Java 21, JSON, Gradle Groovy/Kotlin DSL

**EN:** Stack: Fabric Loader · Fabric API · Fabric Loom · Mixins · Yarn Mappings · Brigadier  
**TR:** Yığın: Fabric Loader · Fabric API · Fabric Loom · Mixin'ler · Yarn Mapping'leri · Brigadier

**EN:** Target: MC 1.21.x (primary), 1.21.1 (LTS baseline), 1.21.8 (active)  
**TR:** Hedef: MC 1.21.x (birincil), 1.21.1 (LTS taban), 1.21.8 (aktif)

---

## 🔥 Contribution Streak / Katkı Serisi

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=tickwarden&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

---

## 📈 Activity Graph / Aktivite Grafiği

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=tickwarden&theme=tokyo-night&hide_border=true&area=true" alt="Contribution Graph" width="95%" />
</p>

---

## 🎮 Development Principles / Geliştirme Prensipleri

| Principle / Prensip | EN | TR |
|---|---|---|
| ✅ **Clean Code** | Readable, maintainable, no hacks | Okunabilir, sürdürülebilir, hack yok |
| ✅ **No Hardcoding** | Dynamic, configurable systems | Dinamik, yapılandırılabilir sistemler |
| ✅ **Security First** | No HTTP abuse, no Desktop API misuse | HTTP kötüye kullanımı yok, Desktop API yok |
| ✅ **MIT Licensed** | Open source, attribution respected | Açık kaynak, atıf hakları korunur |
| ✅ **CI/CD Always** | GitHub Actions on every repo | Her repoda GitHub Actions |
| ✅ **Version Aware** | API verified against real MC source | API gerçek MC kaynağına karşı doğrulanır |

---

## 📫 Contact / İletişim

<div align="center">

[![runtoolkit](https://img.shields.io/badge/GitHub-runtoolkit-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/runtoolkit)
[![ToolkitMC](https://img.shields.io/badge/GitHub-ToolkitMC-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ToolkitMC)

💬 **EN:** Reach out via GitHub Issues on any project repo  
💬 **TR:** Herhangi bir proje reposundaki GitHub Issue'ları üzerinden ulaşabilirsiniz

🌐 **EN:** Active in the Minecraft Java modding community  
🌐 **TR:** Minecraft Java modlama topluluğunda aktif

</div>

---

<div align="center">

### 💡 Open Source · Version Control · Native Java Performance

**EN:** ⭐ If you find these projects useful, a star goes a long way!  
**TR:** ⭐ Bu projeleri faydalı bulduysanız yıldız vermeyi unutmayın!

Made with ❤️ · Legends11

</div>
