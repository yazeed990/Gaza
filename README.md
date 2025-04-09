This project is a responsive Donation website made to support Gaza.  
---


**Important!!**

### ⚠️ Web Dev Tip for Arabic Sites (Mobile Layout Bug)

While working on this project, I faced a very strange layout bug on mobile:

- The screen was cut in half.
- The layout shrinks weirdly on small screens.
- Nothing worked — tried grid fixes, media queries, overflow settings,.. etc.

I literally spent **Over 5 hours debugging** this.   No Kidding

### 🧠 Solution?

```In CSS:
        font-family: "Noto Kufi Arabic";

        ❌ This font breaks responsive layouts.
        ✅ Once I removed this font, everything returned to its proper place instantly.
        ✅ Switching to a safer Arabic font like "Cairo" fixed the issue.

I cried when it worked. If you're building Arabic websites — check your font first.
Hope this helps someone and saves hours of pain. 🙏
