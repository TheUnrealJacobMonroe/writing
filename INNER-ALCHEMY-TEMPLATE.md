# The Inner Alchemy — PBI Creation Template

## Naming Conventions (CRITICAL)

- **Lesson document**: `Book X Lesson Y - {Full Title}` (e.g., "Book 1 Lesson 3 - The Principle of Correspondence")
- **Image**: `Book X Lesson Y.png` (e.g., "Book 1 Lesson 3.png")
- **PBI title**: `Lesson Y: {Title}` (e.g., "Lesson 3: The Principle of Correspondence")

## Google Drive Folder IDs

- **Series root**: `1PBlnVaOUahbIUWX8BblYfKp-MRulr4FD` (/Writing/The Inner Alchemy/)
- **Book 1**: `1Vl9tdNXc6J2fQqXGj9vXQILkbbo94K_H` (/Writing/The Inner Alchemy/Book 1: The Seven Keys of Inner Alchemy/)
- **Book 2**: `1CJ-h3fGWAsQD3CsKzITlEwdOWJRqTq-S` (/Writing/The Inner Alchemy/Book 2: The Alchemy of Daily Life/)
- **Book 3**: `14ZnL1C4gT1GGdl2a8pQOqhkk-OSZVl88` (/Writing/The Inner Alchemy/Book 3: The Living Book of Correspondences/)
- **Book 4**: `1soARGqCwxNPOpAGjChsHYvm1DQ0ZpMtE` (/Writing/The Inner Alchemy/Book 4: The Soul's Ascent/)
- **Book 5**: `1DfCvoDL1N21YmEysZywF6dylFxP1OJWY` (/Writing/The Inner Alchemy/Book 5: Beyond the Veil/)

## Upload Commands

**Lesson as Google Doc:**
```
/root/.openclaw/workspace/scripts/gdocs-create.sh /path/to/lesson.md "Book X Lesson Y - {Title}" --folder {BOOK_FOLDER_ID}
```

**Image upload:**
```
/root/.openclaw/workspace/scripts/gdrive-upload.sh /path/to/image.png {BOOK_FOLDER_ID} "Book X Lesson Y.png"
```

## PBI Task Structure

Each lesson PBI has 4 tasks:
1. **Write Lesson** — Mr. Hemingway (employee 15)
2. **Edit & Review** — The Editor (employee 14)
3. **Generate Hero Image** — Jacob (employee 2)
4. **Commit & Publish** — Jacob (employee 2)

## Lesson 1 Special Case

Lesson 1 of each book is a historical orientation — no 7-section headers. Use natural flow.
Lesson 2+ uses the standard 7-section structure from inner-alchemy-book-style skill.

## Dependencies

Each lesson PBI depends on the previous lesson. PBI N depends on PBI N-1.
Tick will auto-promote next lesson only after previous is Done.
