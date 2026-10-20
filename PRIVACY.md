# Privacy Policy — ExamPrep

**ExamPrep by YomTech** (Amanuel M.)  
Also covers legacy branding as **ExitMOCK** where that name still appears.  
Version 1.2.0 · Effective date: 2026-10-20

## Summary

ExamPrep is a free Ethiopian entrance- and exit-exam practice product from YomTech. It is offered as an **Android (mobile) app**, a **web app** in the browser, and a **desktop app** where published. **Exam questions and tip models are designed to run on your device or in your browser tab** — not on a YomTech account server. The product does **not** require an account and does **not** include ads.

## Platforms this policy covers

- **Mobile app (Android APK / store builds)** — including packages formerly published as ExitMOCK
- **Web app** — browser edition hosted by YomTech (for example on Vercel or a custom domain)
- **Desktop app** — Windows or Linux builds when YomTech ships them for the same product

The same privacy rules apply on every platform unless a section below says otherwise.

## Data stored on your device or browser

Stored locally on your phone, computer, or browser — **not** on YomTech account servers:

- App or site settings (theme, exam options, default tips mode, and similar preferences)
- Optional single best attempt (full Q&A) when “Save my Best” (or equivalent) is on
- Question banks and on-device / in-browser tip models bundled or cached with the product
- On the web: the same kinds of data may use browser storage (for example `localStorage`)

## Network & third parties

- **Loading the web app:** Visiting the website uses ordinary hosting (pages, scripts, question banks). The host may see standard web logs (IP address, user agent, timestamps) as any website does. We do not use that for advertising profiles.
- **Optional network AI tips:** Some builds include a recommender URL. When set, Results may send your attempt (score, answers, questions, timing) to that HTTPS endpoint hosted by the developer. If unreachable, tips fall back to on-device or in-browser models. This is not an ad network.
- **Share / export:** PDF reports, calendar (`.ics`) study schedules, and similar exports stay on your device or go through your OS share sheet / Downloads. We do not receive those files.
- **Crash reports (optional):** Some production builds may include a crash tool (for example Sentry) when configured — crash diagnostics only, not full exam content unless separately documented later.

## Permissions & platform notes

### Android (mobile)

| Permission | Why |
|---|---|
| Storage (API ≤28 only) | Saving PDF exports on older Android; API 29+ uses MediaStore Downloads |

The mobile app does **not** request camera, microphone, location, or contacts.

### Web

Uses normal browser features (storage, optional screen wake lock during an exam, file download for exports). No account login.

### Desktop

Stores settings and optional best attempt on the local machine. Network use matches the optional tips / update behaviour of the build you install.

## Data we collect on our servers

We do **not** run an ExamPrep account system and do **not** collect, store on our servers, or sell personal data from normal product use. Optional tip endpoints and hosting logs are limited as described above.

## Children

The product is for academic exam preparation (including Grade 12 entrance and university exit practice). It does not target children under 13 and does not knowingly collect children’s personal data.

## Contact

- Publisher: YomTech · Amanuel M.
- Email: zeaman48@gmail.com  
- Phone: +251918724038  
- Privacy policy (HTTPS): https://zeaman.github.io/exitmock-privacy/

## Changes

If this policy changes, we will update this page and the Privacy text shown inside the mobile, web, and desktop apps in a future version.

## GitHub Pages

Served from this repository’s root `index.html` (GitHub Pages → `main`).
