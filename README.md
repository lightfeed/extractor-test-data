# HTML to Markdown Test Files for [lightfeed-extract](https://github.com/lightfeed/lightfeed-extract)

This repository contains test files for validating HTML to Markdown conversion functionality. It specifically tests two conversion variants:

1. **Full Conversion** - Converting all HTML content to Markdown
2. **Main Content Extraction** - Extracting and converting only the main content from HTML files

## Repository Structure

```
├── html/             # Source HTML files
│   ├── forum/        # Forum HTML samples
│   │   ├── tech-0.html
│   │   └── ...
│   └── ...
│
└── groundtruth/      # Expected Markdown output files
    ├── forum/        # Expected forum conversion results
    │   ├── tech-0.md         # Full conversion expected output
    │   ├── tech-0.main.md    # Main-content-only expected output
    │   └── ...
    └── ...
```

## Naming Convention

Files follow a specific naming pattern to clearly indicate their purpose:

- `html/[category]/[file-name].html` - Original HTML source files
- `groundtruth/[category]/[file-name].md` - Expected output for full HTML conversion
- `groundtruth/[category]/[file-name].main.md` - Expected output for main content extraction

For example:
- `html/forum/tech-0.html` - Original forum HTML file
- `groundtruth/forum/tech-0.md` - Expected Markdown after full conversion
- `groundtruth/forum/tech-0.main.md` - Expected Markdown when only extracting main content
