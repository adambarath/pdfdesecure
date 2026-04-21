[![Build status](https://ci.appveyor.com/api/projects/status/qoan7ibgh7vcd74r?svg=true)](https://ci.appveyor.com/project/abatsakidis/pdfdesecure)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/16a61ca3fda34415849d93e1f79e731d)](https://www.codacy.com/gh/abatsakidis/PDFDeSecure/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=abatsakidis/PDFDeSecure&amp;utm_campaign=Badge_Grade)

[![Stargazers repo roster for @abatsakidis/PDFDeSecure](https://reporoster.com/stars/dark/abatsakidis/PDFDeSecure)](https://github.com/abatsakidis/PDFDeSecure/stargazers)

# 🛡️ PDFDeSecure

**PDFDeSecure** is a free, open-source tool to remove restrictions from PDF files (e.g. printing, editing, copying), especially when DRM-like protections are applied.

> 📂 Unlock your PDFs from "secured" printing mode in seconds.

---

## ✨ Features

- ✅ Removes PDF security restrictions (print/copy/edit)
- 💡 No need to know the password (if only usage rights are locked)
- 🔐 Works on Adobe LiveCycle DRM-protected PDFs
- 🖥️ CLI support and optional UI
- ⚡ Fast and lightweight — built with C#/.NET
- 💻 Cross-platform via .NET (Windows, Linux, macOS*)

---

## 🚀 Getting Started

### 📦 Download

Grab the latest release from the [Releases page](https://github.com/abatsakidis/pdfdesecure/releases).

Or clone the repo and build it yourself:

```bash
git clone https://github.com/abatsakidis/pdfdesecure.git
cd ./src/pdfdesecure
dotnet build
```

### 🖱️ Usage

```bash
PDFDeSecure.exe input.pdf output.pdf
```

That’s it! Your output PDF will be unrestricted.

### 📚 How it Works

PDFDeSecure bypasses usage restrictions by re-rendering the document as a new PDF, preserving layout and content while discarding the security flags.

⚠️ It does not attempt to crack password-encrypted PDFs (e.g. owner/user password protected).

##🤝 Contributing

Pull requests are welcome! If you’d like to:

    Report a bug ➡️ Open an issue

    Suggest a feature ➡️ Start a discussion

    Help improve UI or compatibility ➡️ Fork and send a PR

Please see CONTRIBUTING.md for details.

## 📄 License

## MIT License © Athanasios Batsakidis

    This tool is provided for educational and legal personal use only. Do not use it on documents you do not own or have rights to modify.
