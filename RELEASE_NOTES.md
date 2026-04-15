# ערבית בכיף — Release Notes

---

## v4.0.0 — 2026-03-19 🚀 The Big Feature Drop

### New Features
- **🗣️ מדריך הגייה** — Interactive pronunciation guide for 13 hard Arabic sounds (ع غ خ ح ق ص ض ط ذ ث ه ر). Each card opens with a description, Palestinian dialect tip, and example words.
- **🤖 שיחה חופשית** — Conversation mode with 3 branching dialogue trees: café with a friend, market bargaining, and asking for directions. Each response choice earns XP.
- **🎉 חגיגת עלייה ברמה** — Confetti explosion + animated celebration popup whenever the player levels up their XP rank.
- **📈 דוח שבועי** — Weekly report modal showing XP, mastered words, games played, streak and total words seen — compared to the previous week with ↑↓ indicators.
- **🔁 Smart Review** — Enhanced spaced repetition using a forgetting curve: words resurface after 1 day, 3 days, or 7 days based on correct-answer history.
- **📴 Offline Mode** — Service worker caches the full app after first load; the site now works with no internet connection.
- **🖨️ הדפס כרטיסיות** — Print/export a 3-column flashcard sheet for any word set (PDF-ready via browser print dialog).
- **📋 הרשימות שלי** — Custom word lists: create named personal lists, add words, and study them in any game mode.
- **📊 Comparison Mode** — Week-over-week XP comparison badge integrated into the weekly report.

---

## v3.5.0 — 2026-03 🎛️ Mega Feature Pack

### New Features
- **🧩 Onboarding Quiz** — 5-question placement quiz on first visit to set the right starting level.
- **📅 Daily Challenges** — Three daily tasks (play a game, learn 5 words, get 3 correct in quiz) with a home widget.
- **🔨 Sentence Builder** — Drag-and-drop style word ordering game.
- **🎵 Song Quiz** — Guess the song from a lyric snippet.
- **📤 Share Score** — Share game results via WhatsApp or copy to clipboard.
- **💬 Phrase of the Day** — A new Arabic phrase shown on the home screen each day.
- **📆 Streak Calendar** — 30-day visual calendar in the stats page showing active days.
- **🗨️ Interactive Dialogues** — Scripted bilingual conversation examples (accordion style).
- **📖 Grammar Tips** — Key Palestinian Arabic grammar rules with examples (accordion style).
- **🔠 Font Size Slider** — Persistent font size control for accessibility.
- **🎶 Playlist Mode** — Sequential song learning — "play all" through the song library.
- **🏅 Expanded Achievements** — New badges for streaks, mastery milestones, and game completions.

### Bug Fixes
- **Speed Race %** — Fixed: success rate exceeded 100% due to combo scoring. Now correctly calculated from correct answers ÷ total.
- **Navbar title** — Fixed "ערבית בשחק" → "ערבית בכיף" in Dialogues, Grammar, and Song Quiz views.
- **Gender labels** — Fixed "גבר" → "זכר" in vocabulary meanings for `من فضلك`, `فرحان`, `صاحب`.

---

## v3.0.0 — 2026-02 🌟 Platform Upgrade

### New Features
- **⚡ XP System** — Earn XP for every game played; level up across 10 tiers.
- **🔥 Daily Streak** — Track consecutive days of practice, saved to localStorage.
- **⭐ Word Mastery** — Each word tracks correct/incorrect history; mastered after 5+ correct answers.
- **❤️ Favorites** — Star any word to add to a personal favorites list.
- **🔍 Search** — Full-text search across all vocabulary.
- **📆 Word of the Day** — New featured word every day on the home screen.
- **📊 Statistics Page** — Charts and counters for XP, streak, mastered words, category progress, and achievements.
- **🔄 Reverse Quiz** — Toggle to flip quiz direction (Hebrew → Arabic).
- **🌗 Dark / Light Mode** — Full theme toggle with localStorage persistence.
- **📱 PWA Support** — App manifest + home screen install for Android/iOS.
- **📲 Mobile Bottom Nav** — Fixed bottom navigation bar on small screens.
- **🎤 Karaoke Mode** — Line-by-line sync in the song learning view.
- **🐛 Report a Bug / 💡 Suggest Update** — Floating feedback buttons (bottom-right) that send details via email.

---

## v2.5.0 — 2026-02 🎵 Songs & Recommendations

### New Features
- **🎵 Learn a Song** — 50+ songs with full lyrics in 4 layers: Arabic script, transliteration, literal translation, free translation.
  - Line-by-line navigation (no scrolling) with swipe, keyboard arrows, and prev/next buttons.
  - Modes: show all / Arabic only / transliteration / literal / meaning.
  - YouTube and Spotify links per song.
- **🎲 Recommendation Lottery** — Random suggestions for Arabic songs, TV shows, books, and podcasts (28 recommendations including Fairuz, Fairouz, Bab El-Hara, Netflix Jordan, and more).
- **🎼 4 Music Styles** — Ambient background music selector: Oud Ambient, Oriental Upbeat, Meditation, Arabic Maqam.

---

## v2.0.0 — 2026-01 📚 Vocabulary Expansion

### Content
- Expanded to **778 vocabulary words** across 20+ categories:
  - Animals (insects, birds, sea creatures), Body Parts, Greetings, Shopping/Money
  - Food (Arab dishes, cooking terms), Home Items, Daily Expressions, Emotions
  - Travel & Transport, Spices, Celebrations, School, City Places
  - Numbers, Days/Months, Verbs, Adjectives, Weather, Pronouns & Questions
  - Conversational phrases (כיף חאלק, אנת מליח, שו האדא...)
  - 12 expressive ABAB verbs (طبطب، بطبط، بجبج، فضفض، فصفص...)
- Added difficulty levels 1–5 to all entries.

### Fixes
- `מתי` → Arabic corrected to `وينتا` (wēnta) in Palestinian dialect.
- "מילות" → "מילים" corrected throughout the site.

---

## v1.0.0 — 2025-12 🌱 Initial Launch

### Features
- Single-page HTML app for learning Palestinian Arabic (no backend, no install).
- **5 vocabulary categories** with Arabic script and Hebrew transliteration.
- **5 difficulty levels** (from "knows only swear words" to "fluent in any Arab country").
- **5 games**: Flashcards, Multiple Choice Quiz, Memory Match, Speed Race, Fill-in-the-Blank.
- Hosted on **GitHub Pages** — accessible from any device.

---

*כל הזכויות שמורות — ערבית בכיף © 2026*
