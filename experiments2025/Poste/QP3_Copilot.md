Good question. Yes — the home page of Poste Italiane (poste.it) **seems to contain a photo / image slider / carousel‑like section**. ([Poste.it][1])

### 🔍 What suggests there is a slider

* In the HTML I see an element for “App Poste Italiane” in the “In evidenza” section, followed by a large image. ([Poste.it][1])
* After that area there are a series of large “offer” blocks — each with a headline (e.g. “Buono Premium 4 anni”, “Promo Creami Extra Wow 50”, etc.) and an associated image. ([Poste.it][1])
* The fact that many of these offers/images appear one after another, and start with “In evidenza”, suggests a rotating banner/slider rather than a static set of images. ([Poste.it][1])

### ⚠️ But — there is no explicit “carousel control” markup visible (in the part of the HTML I inspected)

I did *not* clearly identify, in the HTML snippet I saw, the typical controls of a photo slider (e.g. “next” / “previous” buttons, or a numerical pagination, or a `<div>` with class “slider” / “carousel”). The structure appears as a vertical list of content sections rather than a clearly distinguished `<div>` slider container.

### ✅ Conclusion: likely a “pseudo‑slider / rotating highlight” rather than a strict image‑carousel

From what I see: the page uses big promotional banners and images interspersed with content. This can replicate the *visual effect* of a slider (multiple images/offers displayed in succession), but from the HTML structure it’s **not obviously a conventional slider** (with slider CSS/JS container and controls).

---

If you like — I can **inspect the HTML** more deeply (with a “view source”‑like approach) to try to detect **JavaScript or ARIA landmarks** that explicitly implement a carousel or slider, and then read to you **what a screen reader would announce** when landing on that slider.
Do you want me to do that now?

[1]: https://www.poste.it/ "
      
        Poste Italiane - Servizi postali, finanziari e assicurativi
      
    "
