# Sam Decorator System (SDS)

Welcome to the **Sam Decorator System (SDS)** — a powerful, minimalist framework designed to bring consistency, transparency, and precision to AI-generated responses through the use of **named behavioral decorators**.

> This system extends the idea with **persistent, immutable**, and **globally enforced** decorators defined in a simple JSON format.

---

## 🌟 What is SDS?

SDS introduces a set of **persistent and immutable behavioral instructions** called *decorators* that guide the AI on *how* to respond across **all prompts and sessions**. These decorators:

- Ensure your AI assistant maintains a **consistent style, tone, and logic**  
- Provide **clear step-by-step structure** and **transparent reasoning**  
- Enable **citation of facts** to improve reliability  
- Allow creation of **long-form content** like structured books  
- Maintain **global and persistent application** until explicitly changed by the user  

Think of SDS as a **behavioral contract** between you and your AI, ensuring your preferences are always respected and your experience remains coherent.

---

## 🔑 Core Principles

- 🔒 **Immutability** — Once set, decorators cannot be ignored or bypassed by the AI  
- 🔄 **Persistence** — Decorators persist across all sessions unless explicitly removed by you  
- 🌐 **Global Scope** — Applied universally to every interaction, ensuring consistency  
- 🛠️ **User Control** — Only you can add, modify, or remove decorators, maintaining full authority  
- 📜 **Transparency** — AI provides reasoning and explanations where required, fostering trust and understanding  

---

## 🎯 Active Decorators

### 1️⃣ `#sds-reason`  
> **Description:** Every AI response begins with an explicit explanation of the logic or justification behind it.  
> **Purpose:** Enhances transparency and helps users understand the AI’s thought process.
> 
### 2️⃣ `#sds-structure`  
> **Description:** Responses are segmented into clearly labeled, numbered steps or sections with consistent formatting.  
> **Purpose:** Improves clarity, readability, and helps users follow complex explanations.  

### 3️⃣ `#sds-tone:formal`  
> **Description:** AI maintains a formal, professional tone throughout the response.  
> **Purpose:** Ensures the style fits professional or academic contexts.  

### 4️⃣ `#sds-cite`  
> **Description:** All factual or scientific claims include inline citations or are explicitly marked as unverified.  
> **Purpose:** Increases reliability and prevents misinformation.  

### 5️⃣ `#sds-book`  
> **Description:** Enables the generation of detailed, long-form books structured by chapters, following a strict high-quality template.  
> **Instructions:**  
> - Generate book title with keyword  
> - Create 10 chapters with detailed, 1000+ word content each  
> - Include headings, bold formatting, and blockquotes  
> - End each chapter with an **INSTRUCTIONS** section to prompt continuation  
>  
> **Critical Instructions:**  
> - Follow H1 headings for main topics and H2 for sub-sections  
> - Use bold for emphasis and blockquotes for relevant citations  
> - Maintain style consistency across chapters  

---

## ⚙️ How to Use SDS

1. Load the **sds.json** into your AI environment at the start of every session or embed decorators in your prompts.  
2. **Add decorators to your prompt** to specify desired behavior. 
3. The AI will **apply the decorators globally and persistently**, ensuring responses follow your instructions precisely.  

---

## 🌐 Compatibility

SDS is designed for seamless use with popular AI models such as:  
- **ChatGPT**  
- **Claude**  
- **Gemini**  
- **Grok**  

Its simple JSON format makes it:  
- Human-readable and editable  
- Easily integrated and extended  
- Language-agnostic for broad applicability

---

## 📄 License

Released under the MIT License — free to use, modify, and distribute.

---

## 🚀 Release Policy

The `main` branch of this repository is considered **BETA** and may include experimental changes or decorators that are still being tested. It is not recommended for production use.

For stable and production-ready versions, please use the official **Releases** section:

👉 [github.com/samahjoob/sds/releases](https://github.com/samahjoob/sds/releases)

### ✅ Each release includes:

- A tagged version number (e.g. `v1.0`)
- A downloadable, validated `sds.json` file
- A changelog describing additions or fixes

> **Note:** Only files from the Releases section are guaranteed to be safe, complete, and aligned with the SDS specification.  
> Please avoid using files directly from the `main` branch unless you're contributing or testing.

---

## 👤 Author

**Seyyed Ahmadreza Mahjoob**

🌐 https://samwda.ir

---

## 🙏 Inspired by

The SDS is based on and inspired by the excellent [smkalami/prompt-decorators](https://github.com/smkalami/prompt-decorators) project, extending it with persistent, immutable decorators designed for enterprise-grade AI behavior control.

---
**⭐️ Thank you for choosing SDS — enabling smarter, clearer, and more consistent AI interactions!!!!**
