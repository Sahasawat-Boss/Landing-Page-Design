# ✅ When to Use a Navbar on a Landing Page

Understanding when and how to use a navigation bar on a landing page can improve user experience and conversion.

---

## 🧭 Should You Use a Navbar?

| Scenario                  | Navbar?  | Why                                                                 |
|---------------------------|----------|----------------------------------------------------------------------|
| **Portfolio landing page**     | ✅ Yes   | Users may want to browse projects, contact, about sections           |
| **Product launch page**        | ❌ No    | Keep users focused on a single CTA like "Buy Now" or "Sign Up"       |
| **Single-scroll section page**| ✅ Yes   | Use smooth scrolling nav to “Features”, “Pricing”, “FAQ”             |
| **Ad campaign landing page**  | ❌ No    | Remove distractions to maximize focus on conversion (lead, sale)     |

---

## 🧠 TL;DR

- ✅ **Minimal navbar** with anchor links is fine  
- ❌ **Avoid full nav** if the goal is pure conversion  
- 📌 Use a **sticky navbar** with CTA for long-scroll pages  

---

## 💡 Pro Tip: Minimal, Focused Navbar Example (Tailwind + JSX)

```tsx
<nav className="sticky top-0 z-50 bg-white/80 backdrop-blur-md flex justify-between px-6 py-4">
  <span className="font-bold">BossBSynth</span>
  <ul className="flex gap-6 text-sm">
    <li><a href="#features">Features</a></li>
    <li><a href="#faq">FAQ</a></li>
    <li>
      <a href="#cta" className="btn-primary">
        Get Started
      </a>
    </li>
  </ul>
</nav>
