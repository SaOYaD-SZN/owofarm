# 🌸 OwoFarm

<div align="center">

<!-- Animated Header -->
```
╔═══════════════════════════════════════════════════════════════╗
║                                                               ║
║     ✨ AUTOMATED OWO BOT FARMING SYSTEM ✨                    ║
║     Educational TypeScript Architecture Showcase             ║
║                                                               ║
╚═══════════════════════════════════════════════════════════════╝
```

<!-- Animated Badges -->
<div align="center">
  <img alt="Status" src="https://img.shields.io/badge/status-archived-ff69b4?style=for-the-badge&logo=ghost&logoColor=white">
  <img alt="Purpose" src="https://img.shields.io/badge/purpose-education-8a2be2?style=for-the-badge&logo=books&logoColor=white">
  <img alt="Language" src="https://img.shields.io/badge/language-TypeScript-3178c6?style=for-the-badge&logo=typescript&logoColor=white">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-00D084?style=for-the-badge">
</div>

<br/>

> **Clean Architecture** • **Modular Design** • **Professional Code** • **Educational Value**

</div>

---

## 📌 Quick Links

<table>
<tr>
<td width="50%">

🚀 **[Features](#-features)**

</td>
<td width="50%">

📚 **[Documentation](#-documentation)**

</td>
</tr>
<tr>
<td>

⚡ **[Quick Start](#-quick-start)**

</td>
<td>

🛠️ **[Architecture](#-project-architecture)**

</td>
</tr>
</table>

---

## ⚠️ Important Notice

<div align="center">

```
This repository is ARCHIVED and provided FOR EDUCATIONAL PURPOSES ONLY.
It demonstrates TypeScript architecture patterns and best practices.

⚠️ NOT intended for violating Discord ToS or third-party platforms ⚠️
```

**This project showcases:**
- Clean TypeScript architecture patterns
- Modular command structure
- Task scheduling & retry logic  
- Configuration management best practices
- Maintainable code organization

</div>

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🎯 Core Capabilities
- ⚙️ **Automated Hunting System** - Scheduled auto-hunt with customizable intervals
- ⚔️ **Battle Automation** - Smart battling with timing controls
- 🎲 **Gambling Module** - Configurable gambling interactions
- ⏱️ **Precision Timing** - Millisecond-accurate scheduling
- 🛡️ **Anti-Detection** - Randomized delays and patterns

</td>
<td width="50%">

### 🏗️ Architecture Highlights
- 📦 **Modular Design** - Clean separation of concerns
- 🔧 **Config-Driven** - Flexible JSON configuration
- ⚡ **TypeScript Native** - Full type safety
- 🔄 **Runtime Updates** - Dynamic config reloading
- 📊 **Scalable Structure** - Easy to extend

</td>
</tr>
</table>

---

## 🏗️ Project Architecture

```
owofarm/
├─ 📂 src/
│  ├─ 🔧 config.ts ..................... Configuration loader
│  ├─ 🚀 index.ts ...................... Entry point
│  └─ 📦 modules/
│     ├─ 🎯 hunting.ts
│     ├─ ⚔️ battles.ts
│     ├─ 🎲 gambling.ts
│     └─ 📋 scheduler.ts
│
├─ 📂 config/
│  ├─ your_username.json .............. User configuration
│  └─ defaults.json ................... Default settings
│
├─ 📋 package.json ..................... Dependencies
├─ ⚙️ tsconfig.json .................... TypeScript config
├─ 🔍 .eslintrc.js .................... Linting rules
├─ 💾 .prettierrc ..................... Code formatting
└─ 📖 README.md ....................... This file
```

### 📊 Technology Stack

<div align="center">

| Layer | Technology |
|-------|-----------|
| **Language** | TypeScript 5.x |
| **Runtime** | Node.js 18+ |
| **Build** | tsc |
| **Linting** | ESLint |
| **Formatting** | Prettier |
| **Scheduling** | node-schedule |

</div>

---

## 🚀 Quick Start

### Prerequisites

- **Node.js** 18.0+ ([Download](https://nodejs.org/))
- **npm** 8.0+ (comes with Node.js)
- Discord Account & Token
- Basic command line knowledge

### Installation

#### 1️⃣ **Clone Repository**
```bash
git clone https://github.com/SaOYaD-SZN/owofarm.git
cd owofarm
```

#### 2️⃣ **Install Dependencies**
```bash
npm install
```

#### 3️⃣ **Get Your Discord Token**

<details>
<summary><b>Click to expand token extraction guide</b></summary>

> ⚠️ **Safety Notice:** Never share your token with anyone. Discord tokens are like passwords!

1. **Open Discord in Browser**
   - Navigate to https://discord.com
   - Log in to your account

2. **Open Developer Console**
   - Press `F12` to open Developer Tools
   - Click the **Console** tab

3. **Execute Token Extraction**
   ```javascript
   (w=webpackChunkdiscord_app).push([[Symbol()],{},o=>{try{Object.values(o.c).some(e=>e.exports?.setToken&&(w.t=e.exports.getToken()))}catch{}}]),w.t
   ```

4. **Copy Your Token**
   - Your token will appear in the console
   - Copy and save it safely

</details>

#### 4️⃣ **Configure Environment**
```bash
# Copy example env file
cp .env.example .env

# Edit with your token
nano .env
# Add: DISCORD_TOKEN=your_token_here
```

#### 5️⃣ **User Configuration**

Navigate to the `config` directory and locate your Discord username file:

```bash
cd config
nano your_username.json
```

Update the following IDs:

<details>
<summary><b>Configuration Template</b></summary>

```json
{
  "hunt": "HUNTING_CHANNEL_ID",
  "battle": "BATTLING_CHANNEL_ID", 
  "gamble": "GAMBLING_CHANNEL_ID",
  "pray": "YOUR_USER_ID",
  "curse": "YOUR_USER_ID",
  "cookie": "YOUR_USER_ID",
  "huntInterval": 5000,
  "battleInterval": 8000,
  "gambleInterval": 12000,
  "randomDelay": true,
  "antiDetection": true
}
```

</details>

#### 6️⃣ **Build & Run**

```bash
# Build TypeScript
npm run build

# Run the bot
npm run start

# For development with hot-reload
npm run dev
```

---

## 🎯 Usage

### Running the Bot

```bash
# Production
npm run start

# Development (with file watching)
npm run dev
```

### Console Output

```
✨ OwoFarm Started Successfully
🔧 Configuration: your_username.json loaded
⏱️  Scheduler initialized
🎯 Hunting scheduler: active (interval: 5000ms)
⚔️  Battle scheduler: active (interval: 8000ms)
🎲 Gambling scheduler: active (interval: 12000ms)
```

---

## 🏭 Code Examples

### Custom Module Structure

All modules follow this pattern for consistency:

```typescript
// src/modules/custom-module.ts
export class CustomModule {
  constructor(private config: any) {}
  
  async execute(): Promise<void> {
    // Your logic here
  }
}
```

### Adding a New Command

```typescript
import { CustomModule } from './modules/custom-module';

const module = new CustomModule(userConfig);
await module.execute();
```

---

## 📚 Documentation Structure

### Module Documentation

Each module includes:
- **Purpose** - What the module does
- **Configuration** - Required config fields
- **Methods** - Available functions
- **Error Handling** - Exception management

### Configuration Guide

See detailed configuration options in `config/defaults.json`

---

## 🛡️ Responsible Use Policy

By using this repository, you agree to:

✅ **DO:**
- Study the code architecture
- Learn TypeScript patterns
- Use in educational contexts
- Follow Discord ToS
- Respect platform rules

❌ **DON'T:**
- Violate Discord Terms of Service
- Use for spam/abuse
- Deploy for unauthorized automation
- Share tokens or credentials
- Use on accounts you don't own

> If a use case conflicts with platform terms, **do not use this project for that purpose**.

---

## 🎓 Learning Outcomes

By studying this codebase, you'll understand:

- 🏗️ **Modular Architecture** - How to structure large projects
- 🔌 **Plugin Pattern** - Creating extensible systems
- ⏱️ **Task Scheduling** - Implementing reliable schedulers
- 🔐 **Configuration Management** - Secure config handling
- 📊 **TypeScript Best Practices** - Professional type safety
- 🧪 **Error Handling** - Robust exception management
- 📦 **Project Organization** - Clean file structure

---

## 📝 Contributing

We welcome contributions that align with educational goals:

| Category | Welcome |
|----------|---------|
| 🔧 Code Refactoring | ✅ Yes |
| 📚 Documentation | ✅ Yes |
| 🧪 Unit Tests | ✅ Yes |
| 🏗️ Architecture Improvements | ✅ Yes |
| ⚠️ TOS-Violating Features | ❌ No |

### How to Contribute

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/improvement`)
3. **Commit** your changes (`git commit -m 'Add improvement'`)
4. **Push** to the branch (`git push origin feature/improvement`)
5. **Open** a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** - see the LICENSE file for details.

```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 📞 Support & Questions

### Having Issues?

1. **Check Documentation** - Review the [Quick Start](#-quick-start) guide
2. **Search Issues** - See if your problem is already reported
3. **Read Config** - Verify `your_username.json` is correct

### Report a Bug

- 🐛 Use the GitHub Issues tab
- 📋 Include error messages
- 🔍 Describe reproduction steps

---

## 🎨 Credits & Acknowledgments

<div align="center">

**Made with** 💗 **and** ✨ **by the community**

Thanks to all contributors and supporters!

### Special Thanks

- Original concept & architecture inspiration
- Community feedback and improvements
- Discord API documentation

</div>

---

## 📊 Repository Stats

<div align="center">

![Language Composition](https://img.shields.io/badge/TypeScript-97.9%25-3178c6?style=flat-square)
![JavaScript Support](https://img.shields.io/badge/JavaScript-2.1%25-F7DF1E?style=flat-square)

**Project Age:** Active since 2026  
**Status:** Archived (Educational)  
**Maintenance:** Community-Driven

</div>

---

## 🎯 Roadmap

<div align="center">

### Future Enhancements

- [ ] Comprehensive unit tests
- [ ] API documentation generation
- [ ] Performance benchmarks
- [ ] Advanced logging system
- [ ] Configuration validation schemas
- [ ] Deployment guides

</div>

---

## 🌟 Star History

If you found this educational resource helpful, please consider giving it a star! ⭐

---

<div align="center">

### Made with 💗, TypeScript, and ✨ Attention to Detail

**Last Updated:** August 2026 • **Version:** Educational Release

[⬆ Back to top](#-owofarm)

</div>
