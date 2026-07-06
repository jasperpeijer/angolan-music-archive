
## The Complete Data Directory

```markdown
Angola-Music-Archive/
│
├── 00_Meta/                     # Templates to keep everything uniform
│   └── Template_Artist.md       
│   └── Template_Source.md       
│   └── Template_Lyric.md        
│
├── 01_Sources/                  # Raw inputs (Things you read/hear)
│   ├── Academic_Papers/         # Summaries of research papers
│   ├── Books/                   # Chapter-by-chapter book summaries
│   └── Media_Interviews/        # Notes from video/audio interviews
│
├── 02_Core_Entities/            # The structural pillars of the culture
│   ├── Artists_Bands/           # Profiles of musicians
│   ├── Genres_Movements/        # Deep dives into Semba, Kuduro, etc.
│   ├── Eras_History/            # Eras (e.g., 1961-1974 Anti-Colonial War)
│   └── Instruments_Geography/   # Dikanza, Hungu, Luanda neighborhoods
│
└── 03_Lyrics_Translations/      # The art itself
    ├── Kimbundu/                # Songs primarily in Kimbundu
    └── Portuguese/              # Songs primarily in Portuguese
```

## The Guide to Referencing Books & Papers

When you read a paper or a book, do not just drop quotes randomly. You need a system that tracks _where_ a fact came from so you don't accidentally plagiarize when writing a book, or can properly attribute it on a website.

Every time you read a source, create a single note inside `01_Sources/Academic_Papers/` or `01_Sources/Books/`. Use this precise format:

```markdown
---
type: paper
author: "Moorman, Marissa J."
year: 2004
title: "Dueling Bands and Good Girls: Gender and Music in Luanda's Musseques"
citation_key: "Moorman2004"
---

# Summary
This paper details how Semba music in the 1960s and 70s in the musseques (shantytowns) of Luanda became a vehicle for political resistance against Portuguese colonial rule.

# Key Notes & Quotes
* **Page 4:** "Music was not just a reflection of politics; it was the space where politics were made." -> *Note: Use this quote for the intro chapter on anti-colonial music.*
* **Page 12:** Discusses the band [[Ngola Ritmos]] and how they used Kimbundu lyrics to bypass colonial censors who only spoke Portuguese.

# Linked Entities
* [[Ngola Ritmos]]
* [[Semba]]
* [[Luanda]]
```

### How to use it:

Notice the bracketed terms like `[[Ngola Ritmos]]`? In Obsidian, typing two brackets automatically creates a clickable link to that note. If you are writing a profile on the artist note later, you can look at the bottom of the screen and see exactly which papers referenced them.

## The Complete Lyric Maintenance Guide

Songs are historical texts. To organize them so that a website developer or a book editor can understand them, every song note should map out the language, translation, and historical context.

```markdown
---
song_title: "Mona Ki Ngi Xica"
artist: [[Bonga]]
recorded_year: 1972
language: "Kimbundu"
genre: [[Semba]]
source_reference: [[Moorman2004]]
---

# Context & Analysis
Written by Bonga while in exile. The title means "The child I left behind." It uses the metaphor of an abandoned child to describe the pain of leaving Angola during the liberation struggle.

# Side-by-Side Text

| Original Kimbundu | English Translation | Cultural Notes |
| :--- | :--- | :--- |
| Mona ki ngi xica / O nguma i ngi banga... | The child I left behind / The enemy persecutes me... | "Nguma" (enemy) refers directly to the colonial police state. |
| [Next Line] | [Next Line Translation] | |
```

## Strategic Tips for Gathering Knowledge

Because you are dealing with a niche history that isn't always digitised in English, you have to be clever about how you gather data:

- **Mine the Bibliographies:** When you find _one_ good academic paper (like the works of Dr. Marissa Moorman), don't just read it. Go straight to the end of the document and look at their bibliography. Write down the names of the Portuguese books, Angolan newspapers, or old record labels they cited. That is your next treasure map.
    
- **Track Down the Archives:** Look for digitized versions of historical Angolan cultural journals like _Mensagem_ (from the 1950s) or records from the _Radio Nacional de Angola_.
    
- **Scrape Lyrics with Caution:** Online lyric sites are notoriously full of typos, especially for national languages like Kimbundu or Umbundu. Cross-reference lyric sheets with liner notes from original vinyl records or CDs whenever possible.
    
- **Interview the Diaspora:** If you live near an Angolan community, speak to elders. Ask them what songs played in their households during the 70s or 80s. A single name of a forgotten musician given by an elder can unlock an entire era of research.

## How to Maintain a Project of This Scale

A project like this can easily paralyze you with "organizing panic." Follow three strict rules to keep your sanity:

1. **The 80/20 Maintenance Rule:** Spend 80% of your time actually reading, translating, and writing notes. Spend only 20% of your time organizing folders or making things look pretty.
    
2. **Embrace the "Stub" Note:** If a paper mentions an artist named _David Zé_, do not stop your reading to research his whole life. Just type `[[David Zé]]` in your text. This creates a blank "stub" note. Later, when you have an evening free, you can click on that blank link and fill out his profile.
    
3. **Back Everything Up:** Because Obsidian works entirely via a normal folder on your hard drive, your whole project is just a folder. Use a free service like Google Drive, Proton Drive, or GitHub to keep an automated backup copy of that folder. If your computer breaks, your entire book/website infrastructure remains completely intact.