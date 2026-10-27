# Physics 3 Practice — GitHub Pages

A static Hebrew study site built from the supplied Technion Physics 3 exam archive. Contains **54 original PDF files and 3 DOCX documents** and an automatically indexed subset of question pages; the full original PDFs remain accessible in **ספריית הבחינות המלאה**. Auto-tagging is imperfect and can be corrected per question.

## Publish

1. Create a new public or private GitHub repository (depending on your GitHub Pages plan).
2. Upload **all contents** of this directory to the repository root (including `assets/` and `data.json`).
3. Open **Settings → Pages → Build and deployment → Deploy from a branch**, select `main` and `/ (root)`, then Save.
4. Open the URL GitHub Pages shows you.

To test locally, run `python -m http.server 8000` in this directory and visit `http://localhost:8000`.

### Notes

- The PDF library is complete for the supplied PDF sources, excluding exact duplicates. Three DOCX files from the archive are included for download in the document library, but their questions are not individually indexed.
- A question is indexed only when the text extraction finds an explicit `שאלה N` heading. **Not all questions were indexed**; use the PDF library for the remainder.
- Topic classifications and 'out of scope' filtering are **heuristics**, not verified question-by-question.
- External PDF files were marked as Ziv exams based solely on the user's attribution.
- Progress and personal topic changes are stored locally in the browser. Use the JSON export button for backups. GitHub Pages cannot sync progress between devices without a backend.
- Some PDF source files combine exam questions with solutions on the same page. The reader opens the original page, so solutions may be visible.
