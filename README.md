# HTML to Markdown Test Files for [lightfeed-extract](https://github.com/lightfeed/lightfeed-extract)

This repository contains test files for validating HTML to LLM-extractor-ready Markdown conversion functionality. It specifically tests three conversion variants:

1. **Basic Conversion** - Converting all HTML content to Markdown (without images)
2. **Main Content Extraction** - Extracting and converting only the main content from HTML files (without images)
3. **Conversion with Images** - Converting all HTML content to Markdown including images

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
    │   ├── tech-0.md         # Basic conversion expected output
    │   ├── tech-0.main.md    # Main-content-only expected output
    │   ├── tech-0.images.md  # Conversion with images expected output
    │   └── ...
    └── ...
```

## Naming Convention

Files follow a specific naming pattern to clearly indicate their purpose:

- `html/[category]/[file-name].html` - Original HTML source files
- `groundtruth/[category]/[file-name].md` - Expected output for basic HTML conversion
- `groundtruth/[category]/[file-name].main.md` - Expected output for main content extraction
- `groundtruth/[category]/[file-name].images.md` - Expected output for conversion with images

For example:
- `html/forum/tech.html` - Original forum HTML file
- `groundtruth/forum/tech.md` - Expected Markdown after basic conversion (no images)
- `groundtruth/forum/tech.main.md` - Expected Markdown when only extracting main content (no images)
- `groundtruth/forum/tech.images.md` - Expected Markdown with images included

## Test HTML Files

The HTML test files included in this repository are used solely for testing purposes. All files have been sanitized to replace personal information and sensitive content with generic placeholders. The structure and formatting of the HTML is preserved for testing purposes.
