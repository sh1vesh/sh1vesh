# Install this profile README

Shivesh's public profile repository must be named exactly `sh1vesh`.

Copy both of these items into the repository root:

```text
sh1vesh/
├── README.md
└── assets/
    ├── cover.svg
    ├── field-notes.svg
    ├── work-index.svg
    └── closing-note.svg
```

The `assets` directory is required. Uploading only `README.md` will produce broken
image placeholders because its image paths are relative to the repository.

After committing the files, verify this URL opens successfully:

```text
https://github.com/sh1vesh/sh1vesh/blob/main/assets/cover.svg
```

All four repository-owned SVGs animate without a GitHub Action. The two live GitHub
panels are externally generated and may take a few seconds to appear on first load.
