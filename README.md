<div align="center">

<p>بِسْمِ اللَّهِ الرَّحْمَٰنِ الرَّحِيمِ</p>

# Quran Web3

### Read with clarity. Reflect with purpose. Learn at your own pace.

**An independent Quran reading and learning project built for the modern web.**  
Thoughtfully designed for multilingual access, personal reading continuity, and privacy-conscious use.

<p>
  <img alt="Project status: active development" src="https://img.shields.io/badge/Status-Active%20Development-1f6f64?style=flat-square" />
  <img alt="In development since 2023" src="https://img.shields.io/badge/Since-2023-425b76?style=flat-square" />
  <img alt="12 interface languages" src="https://img.shields.io/badge/UI%20Languages-12-425b76?style=flat-square" />
  <img alt="Built with vanilla JavaScript" src="https://img.shields.io/badge/Frontend-Vanilla%20JavaScript-425b76?style=flat-square" />
</p>

**[The Project](#the-project)** · **[Features](#the-experience)** · **[Architecture](#how-it-is-built)** · **[Languages](#languages)** · **[Project Journey](#the-journey)**

</div>

---

## The Project

Quran Web3 is a long-term, independently developed web application focused on making Quran reading, reflection, and introductory learning more accessible through a clear, responsive interface.

The project brings together Quran reading tools, a structured reading routine, locally saved personal progress, and beginner-friendly learning features. It uses a static-web approach and explores IPFS as an additional way to distribute the application.

**The aim is to keep the experience useful and approachable—not to make technology the center of Quran study.**

## The Experience

| | Feature | What it offers |
|:--:|---|---|
| 📖 | **Quran Reader** | Read by **page** or **surah**, with verse-level navigation, translation, tafsir, and recitation tools. |
| 🔤 | **Arabic Reading Options** | Standard Uthmani text, tajweed-colored display, and word-by-word exploration. |
| 🌍 | **Multilingual Experience** | A user interface in **12 languages**, with multiple Quran translation choices. |
| 🗓️ | **365-Day Khatm** | A structured reading plan with sequential bookmarks and progress that advances when a day is marked complete. |
| 🔖 | **Personal Reading Tools** | Bookmarks, notes, recently read verses, continue reading, and JSON export/import for personal data. |
| 🌿 | **Solace** | Explore Quran verses through eight reflection themes: Anxiety, Sadness, Patience, Gratitude, Anger, Hope, Peace, and Loneliness. |
| ✨ | **Verse of the Day** | A daily verse on the home dashboard, with a direct path to read it in context. |
| 📚 | **Learn to Read Arabic** | An original, six-level beginner-oriented module for recognizing and reading vocalized Arabic script, with practice and progress tracking. |

> **Development note:** The features above describe the current application work and local testing. Content review, quality assurance, and preparation for a new public production release are ongoing. Some features may not be present on historical public demos.

### A reading experience that respects your pace

- **No mandatory account** for the core reading experience.
- **Browser-based personal progress**, with user-controlled export and import.
- **Responsive layouts** and reading preferences for different devices.
- **Learning and reflection tools** designed to complement—not replace—qualified Quran and Arabic teachers.

## Languages

The interface is designed around an English master and localized into the following 12 languages:

| | | |
|---|---|---|
| English (`en`) | Indonesian (`id`) | French (`fr`) |
| Spanish (`es`) | Russian (`ru`) | Portuguese (`pt`) |
| German (`de`) | Chinese (`zh`) | Japanese (`ja`) |
| Korean (`ko`) | Hindi (`hi`) | Bengali (`bn`) |

Interface language support is distinct from the availability of particular Quran translations, reciters, or learning content.

## How It Is Built

Quran Web3 favors maintainable, static-web technologies and a separation between content preparation and the app itself.

| Layer | Approach |
|---|---|
| **Frontend** | HTML, CSS, and vanilla JavaScript |
| **Content preparation** | Python-based data pipeline producing static content assets |
| **Application data** | Structured JSON and related static resources |
| **Personal preferences and progress** | Browser storage, with optional JSON backup and restore |
| **Planned landing and articles** | Cloudflare Pages |
| **Planned application delivery** | 4EVERLAND and IPFS, with HTTPS access through `app.quranweb3.org` |
| **Optional Web3 entry point** | `quranweb3.unstoppable` |

```text
                    QURAN WEB3
                         │
          ┌──────────────┴──────────────┐
          │                             │
  Landing & multilingual blog       Quran web app
       quranweb3.org             app.quranweb3.org
      (Cloudflare Pages)          (Static / IPFS)
          │                             │
    Help people discover         Read • Reflect • Learn
        the project                 Continue reading
                                        │
                              Browser-saved preferences
                                  & personal progress
```

*The domains and delivery services shown here describe the intended production architecture, not a claim that every endpoint is already live.*

## The Journey

**Started in 2023. Evolving with every iteration.**

Quran Web3 began as an exploration of decentralized publishing, Web3 domains, and IPFS. Over time, the focus expanded toward the everyday experience of reading the Quran: accessible page and surah views, multilingual navigation, recitations, study tools, personal reading continuity, a 365-day Khatm plan, Solace, and original Arabic-reading lessons.

Early experiments—including historical Web3 and NFT-related concepts—are part of the project's development history. They do not define the current application's primary purpose.

### Current focus

- Refine Quran content presentation, references, and reading experience.
- Test the reader, Khatm, Solace, and Learn modules across devices and languages.
- Complete release preparation for the static application and multilingual project website.

## Project Presence

- **[GitHub profile](https://github.com/quran-web3)** — project development presence and repository history.
- **[LinkedIn](https://www.linkedin.com/in/quran-web3/)** — project updates and development journey.
- **[Historical project website](https://quran-web3.github.io/)** — earlier landing-page content; a new multilingual website is being prepared.

> The previous experimental deployments are not presented here as the current production application.

## Acknowledgements

Quran Web3 benefits from the work of Quran publishers, translators, scholars, reciters, data contributors, and developers who make Quran resources accessible. The project acknowledges their contributions in its application documentation. Third-party Quran texts, translations, tafsir, and recordings remain associated with their respective sources and rights holders.

---

<div align="center">

**Quran Web3**  
*An independent project. Built with care. Developed since 2023.*

**Read · Reflect · Learn · Continue**

</div>
