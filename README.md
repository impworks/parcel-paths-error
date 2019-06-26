# Parcel paths issue

To reproduce:

1. Clone the repo
2. Open it's root folder in a terminal
3. Execute `parcel build src/index.html`

Expected result: everything builds.

Actual result: `Error: ENOENT: no such file or directory`
