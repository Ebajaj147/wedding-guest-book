# The guest book

An encrypted, password-protected guest planner hosted on GitHub Pages.

Only the encrypted document and its unlock screen are published here. The source document and password are kept outside this repository. The page uses AES-256-GCM and PBKDF2-SHA-256 with 600,000 iterations.

A strong shared password is required. Refreshing or selecting Lock closes the document. Passwords are not stored in browser storage by this page.
