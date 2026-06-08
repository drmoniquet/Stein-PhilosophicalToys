---
name: Custom issue template
about: Notes
title: ''
labels: ''
assignees: ''

---

cd your-repo

git init                      # if new
git add index.html
git commit -m "blind glass: lens reader for Tender Buttons (first working version)"

git add lexicon.json
git commit -m "move the lexicon out to lexicon.json so I can edit data without touching the html"

git add a-blind-glass-statement.md
git commit -m "add artist statement"

git add build_docx.js a-blind-glass-lexicon.docx
git commit -m "script to spit out an editable .docx from the lexicon"

# then the touch fix 
git commit -am "fix: glass wouldn't drag on iphone — needed touch-action:none (safari steals it as a scroll)"
