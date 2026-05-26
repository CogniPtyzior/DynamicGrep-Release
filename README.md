# Dynamic Grep

**Dynamic Grep** is a local-first desktop application for powerful text search, extraction, inspection and reporting across many file formats.

It is designed for users who need to search through folders, documents, logs, source code, archives or project files without modifying the original content.

Dynamic Grep runs locally on your computer. It does not require a cloud account, a remote server or an internet connection for normal usage.

---

## Product overview

| Item | Description |
|---|---|
| Product name | Dynamic Grep |
| Technical name | DynamicGrep |
| Publisher | Damien Farina |
| Application type | Desktop application |
| UI technology | Avalonia desktop GUI |
| Supported platforms | Windows x64, Linux x64 |
| Distribution format | Portable packages |
| Primary purpose | Local search, extraction, analysis and reporting |
| Data model | Local-first |
| License | Damien Farina |

---

## Download

Portable release packages are available from the GitHub Releases page.

Available packages:

```txt
DynamicGrep-win-x64-portable.zip
DynamicGrep-linux-x64-portable.tar.gz
```

Choose the package matching your operating system:

| Platform | Package |
|---|---|
| Windows 10/11 x64 | `DynamicGrep-win-x64-portable.zip` |
| Linux x64 desktop | `DynamicGrep-linux-x64-portable.tar.gz` |

---

## What Dynamic Grep does

Dynamic Grep helps users search, inspect and understand large sets of local files.

The application provides a desktop interface to run searches across folders, review matching results with context, compare search sessions and export reports.

It is useful when you need to:

- Find a word, phrase, pattern, identifier or expression across many files.
- Search through a project directory, documentation folder, logs folder or archive.
- Inspect matches with highlighted excerpts and surrounding context.
- Compare results from different searches.
- Generate readable HTML reports.
- Keep a local history of recent searches when enabled.
- Open, reveal, copy or export useful search results.
- Work offline without sending files to a remote service.

Dynamic Grep is intentionally designed as a **read-only analysis tool**.  
It helps you find and understand file content, but it does not perform massive replace operations or modify the contents of searched files.

---

## Main features

### Local-first desktop search

Dynamic Grep runs locally on your machine.

Your files remain on your computer during normal use. The application does not require a server, an online account or a cloud synchronization service.

This makes it suitable for:

- Source code search
- Local documentation review
- Log inspection
- Configuration file analysis
- Offline document search
- Project folder exploration
- Local audit and reporting tasks

---

### Multiple search modes

Dynamic Grep supports several search modes:

- **Keyword search** for simple text lookup.
- **Regex search** for advanced pattern matching.
- **Wildcard search** for flexible filename-like or text-like patterns.

These modes allow both simple and advanced search workflows depending on the user’s needs.

---

### Contextual result inspection

Search results are displayed with contextual previews.

Each match can include surrounding text, making it easier to understand the result without opening every file manually.

The application focuses on helping users answer questions such as:

- Where is this term used?
- In which files does this expression appear?
- What is the surrounding context?
- Is this result relevant?
- Should this file be opened, copied or included in a report?

---

### Highlighted matches

Dynamic Grep highlights matching text inside result previews.

This improves readability when scanning large result sets and helps users quickly identify why a file matched the search query.

---

### Reports

Dynamic Grep can generate static HTML reports.

Reports may include:

- Search metadata
- Matching files
- Highlighted excerpts
- Diagnostic information
- Search output suitable for review or sharing

Reports are stored locally and can be opened with a web browser.

---

### Recent searches

When enabled in privacy settings, Dynamic Grep stores recent searches locally.

This allows users to quickly return to previous search sessions without reconfiguring the same query and folder every time.

Recent searches remain local to the machine.

---

### Search session comparison

Dynamic Grep includes an architecture for comparing search sessions.

This can help users understand differences between two searches, compare result sets, or review how search output changes over time.

---

### Safe file actions

Dynamic Grep provides safe actions for working with results:

- Open a matched file.
- Reveal a file in the file explorer.
- Copy a file path.
- Copy an excerpt.
- Copy selected files to another destination.
- Move selected files to the local Dynamic Grep trash with confirmation.

The application is designed to avoid destructive file operations by default.

---

## Supported file usage

Dynamic Grep is intended for searching local files and folders such as:

- Source code files
- Text files
- Markdown documents
- Configuration files
- Logs
- Documentation folders
- Text-like files
- Supported archive text entries

Some document formats may depend on extraction support and system configuration.

---

## Supported platforms

Dynamic Grep currently supports:

- Windows 10/11 x64
- Linux x64 desktop

Not supported in this release:

- macOS / OS X
- Mobile platforms
- Web-only usage

---

## Installation

## Windows

### 1. Download the Windows package

Download:

```txt
DynamicGrep-win-x64-portable.zip
```

from the GitHub Releases page.

### 2. Extract the archive

Extract the archive to a folder of your choice.

Example:

```txt
C:\Tools\DynamicGrep\
```

### 3. Run the application

Open the extracted folder and run:

```txt
DynamicGrep.App.exe
```

### 4. Optional: create a shortcut

You can create a desktop shortcut to `DynamicGrep.App.exe` for easier access.

### Windows SmartScreen note

The Windows binary is not code-signed yet.

Windows SmartScreen may display a warning when running the application for the first time. This can happen with unsigned independent software.

Only continue if you downloaded the archive from the official GitHub Releases page.

---

## Linux

### 1. Download the Linux package

Download:

```txt
DynamicGrep-linux-x64-portable.tar.gz
```

from the GitHub Releases page.

### 2. Extract the archive

```bash
tar -xzf DynamicGrep-linux-x64-portable.tar.gz
```

### 3. Enter the extracted folder

```bash
cd DynamicGrep
```

### 4. Make the application executable if needed

```bash
chmod +x DynamicGrep.App
```

### 5. Run the application

```bash
./DynamicGrep.App
```

### Linux desktop integration note

Depending on your Linux distribution and desktop environment, clipboard integration and file explorer actions may vary.

---

## Portable package contents

The portable packages include the application and offline documentation.

Typical package layout:

```txt
DynamicGrep.App.exe / DynamicGrep.App
docs/
  user-help/
  architecture.md
  specifications.pdf
```

The bundled documentation is intended to help users understand the application directly from the portable package.

---

## Privacy

Dynamic Grep is local-first.

Normal usage does not require:

- A cloud account
- A remote server
- Internet access
- Online synchronization
- Uploading files to an external service

Logs and diagnostic bundles are designed not to include full file contents or full extracted text by default.

Users should still review diagnostic bundles before sharing them externally.

---

## What Dynamic Grep does not do

Dynamic Grep is not intended to provide:

- Massive replace
- Direct file content editing
- Archive modification
- Cloud synchronization
- HTTP API usage
- Plugin execution
- Semantic search
- macOS support in V1

The application focuses on local search, inspection, reporting and safe result handling.

---

## Known limitations

- OCR is experimental and disabled by default.
- Legacy Office formats are best-effort and may require LibreOffice.
- PDF extraction works best when the PDF contains a text layer.
- Linux clipboard integration depends on the desktop environment.
- Linux file explorer integration depends on the desktop environment.
- Windows binaries are not code-signed yet.
- macOS is not supported in this release.

---

## Recommended usage examples

Dynamic Grep can be used to:

- Search for a function name across a source code repository.
- Find a configuration key across multiple environment files.
- Inspect logs for a specific error code.
- Search Markdown or documentation folders.
- Identify files containing a specific business term.
- Prepare a local report of matching results.
- Compare two search sessions.
- Review project folders without modifying files.

---

## Release notes

This release provides portable Windows and Linux desktop packages.

To use the application:

1. Download the package matching your operating system.
2. Extract the archive.
3. Run the application executable.
4. Select a folder to search.
5. Enter a search query.
6. Review, export or report the results.

---

## License

License: Damien Farina

Copyright © Damien Farina

All rights reserved unless explicitly stated otherwise.