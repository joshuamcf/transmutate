# transmutate
Paste reviewed Word content to get content-ready HTML and Optimizely page fields.

Handles both:
- older Word documents (Word styles, `[H2]` markers, a Source references table), and
- documents prepared with the maintenance-document-preparation skill (`[Meta title]`, `[Meta description]`, `[H1]`–`[H3]` markers, `[Source references HTML]`).

Open `index.html` in a browser. It is a single file with no build step. The redirect list sits between the `REDIRECT-DATA-START` and `REDIRECT-DATA-END` markers; use "Maintaining the redirect list" in the tool to rebuild it.
