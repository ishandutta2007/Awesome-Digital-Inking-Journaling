# Awesome-Digital-Inking-Journaling

# Awesome-Digital-Inking-Journaling



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Handwriting Recognition, PDF Annotation, Infinite Canvas & Digital Journaling*

**Last updated: October 2026**



This repository tracks notable **commercial apps** and **open-source projects** for **Digital Inking & Journaling**. These tools help users write, sketch, and annotate by hand on tablets, convertibles, and styluses—preserving the tactile feel of pen and paper while adding digital superpowers like search, sync, and PDF markup.



**Examples** include Microsoft Journal, GoodNotes, Notability, Nebo, OneNote, Penbook, Noteful, Concepts, Paper by WeTransfer, and Noted (the category leaders).



**Open-source emphasis**: The open-source inking ecosystem is **exceptionally mature and production-proven**. **Xournal++** is the definitive open-source handwriting app with vector-based ink, PDF annotation, LaTeX support, audio-synchronized notes, and Lua scripting . **Rnote** brings an adaptive infinite canvas built in Rust and GTK4, targeted at students and drawing-tablet users . **Saber** delivers cross-platform handwritten notes with self-hosting, dark-mode ink inversion, and a dual-password encryption system . This section documents these production-grade solutions.



## 📖 Table of Contents



- [💼 Commercial Apps](#-commercial-apps)

- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)

- [🤝 How to Contribute](#how-to-contribute)

- [⚠️ Disclaimer](#-disclaimer)



## 💼 Commercial Apps



> **📊 Market Context**: The digital journaling and inking market is **moderately fragmented**, driven by tablet adoption and remote work. **GoodNotes** dominates iPad inking with fluid digital ink and AI handwriting recognition . **Microsoft Journal** is bundled free with Windows for pen-enabled devices. **Notability** pioneered audio-synchronized note-taking on iPad. **Nebo** leads in handwriting-to-text conversion across platforms. The market is **highly concentrated on Apple ecosystems** for premium inking apps, while **Windows and Android** rely more on bundled tools (OneNote, Samsung Notes) and cross-platform apps. No single vendor holds a winner-take-all position; users typically pick based on platform and stylus hardware.



| App | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |

|-----|-------------|------------------------|------------------|--------------|

| **[Microsoft Journal](https://www.microsoft.com/en-us/p/journal/9nblggh4qghw)** | **Free Windows inking app for pen-first note-taking.** Ink gestures, lasso selection, and automatic page organization. | **Free** — bundled with Windows 10/11. | **Unlimited** — free with Windows. | **~$281B revenue (Microsoft FY2025)** |

| **[GoodNotes](https://www.goodnotes.com/)** | **The leading iPad handwriting app.** Fluid digital ink, AI handwriting recognition, notebook organization, and cross-platform sync . | **Free** with limited notebooks; **Premium** subscription or one-time purchase for unlimited. | **Free tier**: Limited notebooks and features. **Paid**: Unlimited notebooks, AI features. | **Private (GoodNotes)** |

| **[Notability](https://www.gingerlabs.com/)** | **Audio-synchronized note-taking for iPad and Mac.** Record lectures while writing; tap ink to jump to the audio moment. | **Free** with limited edits; **Premium** subscription. | **Free tier**: Limited monthly edits. **Paid**: Unlimited editing and audio. | **Private (Ginger Labs)** |

| **[Nebo](https://www.nebo.app/)** | **Cross-platform handwriting-to-text conversion.** Write by hand, get editable text instantly. | **Free** with basic features; **Pro** one-time purchase. | **Free tier**: Basic note-taking. **Paid**: Unlimited conversion, PDF import/export. | **Private (MyScript)** |

| **[OneNote](https://www.microsoft.com/en-us/microsoft-365/onenote/digital-note-taking-app)** | **Microsoft's free-form note app with inking support.** Stylus input on Windows, iPad, and Android. | **Free** — bundled with Microsoft 365 or standalone. | **Unlimited** — free with Microsoft account. | **~$281B revenue (Microsoft FY2025)** |

| **[Penbook](https://www.penbookapp.com/)** | **Beautiful journaling app for iPad.** Hand-crafted paper backgrounds and ink experiences. | **Free** with limited journals; **Premium** subscription. | **Free tier**: Limited journals and backgrounds. | **Private (Penbook)** |

| **[Noteful](https://www.noteful.com/)** | **iPad note-taking with layers and natural ink.** One-time purchase model. | **One-time purchase** on App Store. | **No free tier**. Paid app. | **Private (Noteful)** |

| **[Concepts](https://concepts.app/)** | **Infinite canvas sketching and design.** Vector-based drawing for ideation and concept work. | **Free** with limited tools; **Pro** subscription. | **Free tier**: Basic brushes and canvas. **Paid**: Full toolset. | **Private (TopHatch)** |

| **[Paper by WeTransfer](https://paper.bywetransfer.com/)** | **Minimalist sketching and journaling.** Beautiful ink tools on an infinite canvas. | **Free** with limited tools; **Pro** subscription. | **Free tier**: Basic sketching tools. | **Part of WeTransfer** |

| **[Noted](https://www.notedapp.io/)** | **Audio-first note-taking app.** Record and transcribe meetings, lectures, and ideas. | **Free** with limited recording; **Premium** subscription. | **Free tier**: Limited recording hours. | **Private (Noted)** |



## 🔓 Open-Source GitHub Projects



| Repo | Description | Stars |

|------|-------------|-------|

| **[Xournal++](https://github.com/xournalpp/xournalpp)** — **The definitive open-source handwritten note-taking app.** **C++/GTK3**, vector-based ink rendering. **Pressure-sensitive stylus support** (Wacom, Huion, XP-Pen). **PDF annotation** with movable ink layers. **LaTeX support** for math. **Audio recording synchronized to handwriting**—tap a stroke to jump to the audio moment. **Shape recognition, splines, set-square and compass tools**. **Lua scripting** for plugins. Export to SVG, PNG, PDF. Cross-platform (Linux, macOS, Windows). **GPL-2.0** . | [![Stars](https://img.shields.io/github/stars/xournalpp/xournalpp?style=social&color=white)](https://github.com/xournalpp/xournalpp/stargazers) | ~12,000 |

| **[Rnote](https://github.com/flxzt/rnote)** — **Vector-based sketching and handwritten notes with infinite canvas.** **Rust/GTK4**, adaptive UI focused on stylus input. **Infinite canvas** with configurable expansion layouts (fixed pages, continuous vertical, infinite every direction). **PDF, bitmap, and SVG import/export**. Native `.rnote` file format (gzipped JSON). **Optional pen sounds**. **CLI for automation**. Cross-platform (Linux Flatpak, macOS app bundle, Windows installer via winget). **GPL-3.0** . | [![Stars](https://img.shields.io/github/stars/flxzt/rnote?style=social&color=white)](https://github.com/flxzt/rnote/stargazers) | ~8,000 |

| **[Saber](https://github.com/saber-notes/saber)** — **The notes app built for handwriting, available everywhere.** **Flutter-based**, cross-platform (Android, iOS, Linux, Windows, macOS, Web). **Dual-password system** protects notes even if the server is compromised. **Self-hosting supported** (official server, another server, or your own). **Dark-mode ink inversion** (white ink on black background). **Highlighter with canvas compositing** for consistent multi-line highlighting. **Unlimited nested folders**. Open-source so anyone can inspect data handling. **GPL-3.0** . | [![Stars](https://img.shields.io/github/stars/saber-notes/saber?style=social&color=white)](https://github.com/saber-notes/saber/stargazers) | ~3,000 |

| **[Linwood Butterfly](https://github.com/LinwoodCloud/Butterfly)** — **Powerful, minimalistic, cross-platform open-source note-taking app.** Infinite canvas, stylus support, import/export PDF/SVG/images, WebDAV sync, offline use, FOSS. **Active development** with frequent releases (2.4.2 in Dec 2025). Android, Windows, Linux, Web . | [![Stars](https://img.shields.io/github/stars/LinwoodCloud/Butterfly?style=social&color=white)](https://github.com/LinwoodCloud/Butterfly/stargazers) | ~2,000 |

| **[SimpleJournal](https://github.com/andyld97/SimpleJournal)** — **Simple Windows program for drawing and writing with tablets, convertibles, or mouse.** **WPF/.NET 10**, available in Normal and Store (MSIX) versions. Features: paper formats, page patterns (chequered, dotted, ruled, blank), **PDF support** (requires Ghostscript), automatic updates, **disable-touch feature** to prevent palm input, backup and auto-save, text and form recognition, custom drawing tools. Inspired by Windows Journal . | [![Stars](https://img.shields.io/github/stars/andyld97/SimpleJournal?style=social&color=white)](https://github.com/andyld97/SimpleJournal/stargazers) | ~200 |

| **[SpeedyNote](https://alternativeto.net/software/speedynote/about/)** — **Built for classic tablet PCs, low-resolution screens, and vintage hardware.** GPL-3.0 licensed, native C++/Qt. Delivers **360Hz stylus input on modest hardware** . | [![SpeedyNote](https://img.shields.io/badge/SpeedyNote-App-blue)](https://alternativeto.net/software/speedynote/about/) | N/A |

| **[Lorien](https://github.com/mbrlabs/Lorien)** — **Infinite canvas drawing/note-taking app.** Free and open source . | [![Stars](https://img.shields.io/github/stars/mbrlabs/Lorien?style=social&color=white)](https://github.com/mbrlabs/Lorien/stargazers) | ~1,000 |

| **[Scrivano](https://github.com/TeXlyre/Scrivano)** — **Handwriting and PDF annotation app.** Tested alongside Xournal++ and Rnote for stylus Linux apps . | [![Stars](https://img.shields.io/github/stars/TeXlyre/Scrivano?style=social&color=white)](https://github.com/TeXlyre/Scrivano/stargazers) | ~500 |



**Additional open-source options worth exploring:**



| Repo | Description |

|------|-------------|

| **[Agaric](https://github.com/jfolcini/agaric)** — Local-first, block-based journaling app with Rust backend, journal view, tags, backlinks, peer-to-peer sync over local WiFi, and Mermaid diagrams . |

| **[Joplin](https://github.com/laurent22/joplin)** — Privacy-focused note-taking with handwriting support via plugins, E2E encryption, and Nextcloud/WebDAV sync . |

| **[Writernote](https://github.com/writernote/writernote)** — Take notes in an intelligent way . |

| **[Write (Stylus Labs)](https://github.com/styluslabs/write)** — Designed for note-taking, brainstorming, and sketching . |



## 🤝 How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's commercial or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## ⚠️ Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Digital inking apps handle potentially sensitive personal notes and journal entries; review privacy policies and data storage practices before use.

- **Open-source reality**: The open-source ecosystem for digital inking is **exceptionally mature and production-proven**. **Xournal++** is the definitive open-source handwriting app with vector-based ink, PDF annotation, LaTeX support, and audio-synchronized notes . **Rnote** brings an adaptive infinite canvas built in Rust . **Saber** delivers cross-platform handwritten notes with self-hosting and dual-password encryption . However, **commercial apps** (GoodNotes, Notability) provide **polished UX, seamless cloud sync, and advanced AI features** that open-source alternatives may lack. The open-source path is **genuinely viable** for students, researchers, and privacy-conscious users seeking full data ownership.

- **Hardware caveat**: Rnote **does not work properly on X11** — stylus and touch input support is unreliable, and upstream GTK4 support will decrease over time . Wayland is required for the best experience.



---



**Made for students, researchers, digital journalers, and anyone who thinks better with a stylus.**

Let's make digital inking more open, transparent, and user-controlled.
