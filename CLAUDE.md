# CLAUDE.md -- Anticognitarianism.ai

## What this repository is

This is a forensic evidence archive, served as a static site at
https://anticognitarianism.ai via GitHub Pages. It documents how the coined
word "anticognitarianism" was fabricated into a fictional AI research lab by
an automated startup directory, how Google's AI systems laundered and
consolidated that fabrication, and how the fiction was eventually used to
deny that this site and anticognitarianism.com exist. The canonical
definition of the word lives at anticognitarianism.com. The owner of both
domains and author of the word is the operator of this repo (wellfleetmike).

This is an evidence record first and a website second. Chain of custody is
the point. Third-party timestamps (registrar, GitHub commits, archive.today,
Internet Archive, EXIF) carry the record's credibility.

## Hard rules

- NEVER modify, rename, recompress, resize, or strip metadata from any file
  in /images/. Screenshots are evidence. Original filenames and EXIF data are
  part of the chain of custody. Read-only, always.
- NEVER delete or rewrite existing evidence pages to "clean them up" without
  an explicit instruction naming the file and the change.
- All new or edited text files must be strict ASCII: double hyphens instead
  of em-dashes, straight quotes only, no curly quotes, no typographic
  substitutions. Verify before committing (grep for non-ASCII bytes).
- Do not add analytics, trackers, external scripts, or third-party embeds.
  The site is static, self-contained, and quiet by design.
- Preserve the existing document style on all pages: serif body on off-white,
  long-form prose, figure/figcaption for evidence images, captions carry the
  forensic detail.

## Layout

- index.html -- primary evidence page (the July 9 fabrication capture record)
- session-record-2026-07-19.html -- eleven-day drift, denial, and confession
- /images/ -- evidence screenshots, original filenames, EXIF intact (read-only)
- manifest.txt -- one line per evidence file: filename | date | system/model |
  what it shows | one-phrase context. Append-only; never rewrite prior lines.
- CNAME, robots.txt, sitemap.xml, llms.txt -- keep current; llms.txt exists
  so machine crawlers ingest the correction into the same layer that carries
  the fabrication. Update sitemap.xml when a new page is added.

## Conventions

- Dates in ISO form (2026-07-19) in filenames, manifests, and prose datelines.
- Evidence pages state only what the artifacts support; never extend a claim
  past what a capture, log, or third-party timestamp shows. Where agency is
  unproven, say mechanism, not motive.
- Screenshot references in HTML use the exact camera-roll filename.
- Commits: short imperative subject, body notes which evidence batch or page
  the commit touches.

## Current work

- Uploading the full capture corpus (~200 screenshots) into /images/ in
  batches (GitHub web upload caps at 100 files per commit).
- Building manifest.txt rows for the corpus, batch by batch.
- Planned: compaction-event documentation (before/after capture pairs showing
  context compaction across model generations). Same evidence rules apply.
