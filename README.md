# TriFreedom — तीन आज़ादियाँ। एक ज़िंदगी।

**trifreedom.in** — ek awareness movement: zindagi me 3 freedoms pane ke liye —

| | Freedom | Matlab |
|---|---|---|
| 🕐 | **समय (Time)** | Apna din khud chunna — kisi aur ke order se nahi |
| 💚 | **स्वास्थ्य (Health)** | Tan-man ki taaqat — dawaiyon aur dar pe nahi, aadaton pe bharosa |
| 📈 | **धन (Wealth)** | Befikri — paisa aapke liye kaam kare, aap paise ke liye nahi |

> Bina kisi tension ke, bina kisi ke control ke — apni sharton pe jiyi gayi zindagi.

## Tech

Bilingual (English default + हिंदी toggle, nav button, localStorage-persisted). Pure static site — koi framework nahi, koi build step nahi. `index.html` + `style.css`, bas.
Isliye hamesha fast, hamesha zero-maintenance.

- Fonts: Mukta + Tiro Devanagari Hindi (Google Fonts)
- Animations: CSS + ek chhota IntersectionObserver
- Hosting: GitHub Pages (push to `main` → live)

## Deploy

`main` pe push karo → GitHub Pages khud publish kar deta hai. Kuch aur nahi karna.

Custom domain: `trifreedom.in` (CNAME file me set hai; DNS Hostinger pe manage hota hai —
apex A records → GitHub Pages IPs: 185.199.108.153 / .109.153 / .110.153 / .111.153,
`www` CNAME → `trinexus-system.github.io`).

---

*Ek sapna — sabki aazadi.* 🔺
