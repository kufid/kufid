# 🥸 KUFID

**Kinda Unnecessary Funny Identifier**  
_A completely unnecessary alternative to UUIDs — and proud of it._

🚧 This project is under construction.  
📦 `npm install kufid` → coming soon  
🥸 We're working on something uselessly delightful.

---

## 🤔 What's KUFID?

KUFID is a JavaScript/TypeScript library that generates **human-readable**, **word-based**, and **number-free** identifiers.  
Because cryptic strings like `f47ac10b-58cc-4372-a567-0e02b2c3d479` are great for machines...  
…but maybe your brain prefers `fluffy-pancake` instead 🥞

KUFIDs are not globally unique, not ISO-compliant, and definitely not serious.  
They’re just fun little word combos that make dev logs more… readable.

---

## 💬 Why does KUFID exist?

Because UUIDs are:
- Long
- Cold
- Unpronounceable

…and because sometimes you want an ID like `angry-goose` in your console.

---

## ✨ Features (actual and upcoming)

- ✅ 100% **word-based** IDs — no numbers, no gibberish
- ✅ Human-friendly and vaguely memorable
- ❌ Not cryptographically secure — that's kind of the point
- 🔜 Themes, emoji modes, and francophone flair
- 🧼 Optional “safe mode” to avoid spicy words

---

## 🧪 Example

```ts
import { kufid } from 'kufid'

const id = kufid()
// → 'grumpy-poutine'
