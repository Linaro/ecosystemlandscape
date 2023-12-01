---
layout: project
permalink: /:title/
category: libraries

meta:
  keywords: "Tesseract"

project:
  title: "Tesseract"
  type: "C++"
  ci_url: "https://ci.appveyor.com/project/zdenop/tesseract/"
  url: "Tesseract"
  project_official_url: "https://github.com/tesseract-ocr/tesseract"
  logo: "/assets/images/projects/middleware/tesseract/logo.png"
  overview: "Tesseract is an optical character recognition engine for various operating systems.It is free software, released under the Apache License. Originally developed by Hewlett-Packard as proprietary software in the 1980s, it was released as open source in 2005 and development has been sponsored by Google since 2006. Tesseract was in the top three OCR engines in terms of character accuracy in 1995. It is available for Linux, Windows and Mac OS X. Tesseract up to and including version 2 could only accept TIFF images of simple one-column text as inputs. These early versions did not include layout analysis, and so inputting multi-columned text, images, or equations produced garbled output. Since version 3.00 Tesseract has supported output text formatting, hOCR positional information and page-layout analysis. Support for a number of new image formats was added using the Leptonica library. Tesseract can detect whether text is monospaced or proportionally spaced."

supported_releases:
  - release:
    version: "5.3.3"
    url: "https://github.com/tesseract-ocr/tesseract/releases/tag/5.3.3"
  - release:
    version: "5.3.2"
    url: "https://github.com/tesseract-ocr/tesseract/releases/tag/5.3.2"
  - release:
    version: "5.3.1"
    url: "https://github.com/tesseract-ocr/tesseract/releases/tag/5.3.1"

work_items:
  - work:
    title: "Check if NEON extension are actually available"
    url: "https://github.com/tesseract-ocr/tesseract/pull/4154"
    status: "Open"
  - work:
    title: "Fix code for generating config files"
    url: "https://github.com/tesseract-ocr/tesseract/pull/4074"
    status: "Open"
  - work:
    title: "Allow for text angle/gradient to be retrieved"
    url: "https://github.com/tesseract-ocr/tesseract/pull/4070"
    status: "Open"

---

<p>Tesseract</p>
