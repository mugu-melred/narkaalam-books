# narkaalam-books

Public-domain book texts used by the Narkaalam app (Learn > Books). One JSON file per book part: `books/<key>/<part>.json`, each `[[chapterTitle, [paragraph, ...]], ...]`.

Sources (all public domain): Tamil texts from Project Madurai (https://www.projectmadurai.org/), English texts from Project Gutenberg (https://www.gutenberg.org/). Only authors who died before 1966 (or ancient works) are included.

Rebuild from the app repo: `BOOKS_OUT=<this folder>/books node --experimental-strip-types scripts/build-books.mjs`
