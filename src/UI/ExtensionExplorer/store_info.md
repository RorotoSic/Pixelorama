// This file is for online use.<br>

## Rules for writing a (store_info) file:
// 1. The Store Entry is one large Array (referred to as "entry") consisting of sub-arrays (referred to as "data")<br>
// e.g `[[keyword, ....], [keyword, ....], [keyword, ....], .......]`<br>
// 2. Each data must have a keyword of type `String` at it's first index which helps in identifying what the data represents.<br>
// e.g, ["name", "name of extension"] is the data giving information about "name".<br>
// Valid keywords are `name`, `version`, `description`, `tags`, `thumbnail`, `download_link`<br>
// Put quotation marks ("") to make it a string, otherwise errors will occur.<br>
// 3. One store entry must occupy only one line (and vice-versa).<br>
// 4. Comments are supported. You can comment an entire line by placing `#` or `//` at the start of the line. Comments between or at end of line are not allowed.<br>
// 5. Links to another store_info file can be placed inside another store_info file, and it will get detected as a custom store file.<br>

## TIPS:
// - `thumbnail` is the link you get by right clicking an image (uploaded somewhere on the internet) and selecting Copy Image Link.<br>
// - `download_link` is usually of the form `{repo}/raw/{Path of extension within repo}`<br>
// e.g, if `https://github.com/Variable-ind/Pixelorama-Extensions/blob/master/Extensions/Example.pck` is the URL path to your extension then replace "blob" with "raw"
// and the link becomes `"https://github.com/Variable-ind/Pixelorama-Extensions/raw/master/Extensions/Example.pck"`<br>

// For further help see the entries below for reference of how it's done
## Entries:
[["name", "LospecPaletteImporter"], ["version", 1.1], ["description", "A Pixelorama extension for downloading and importing palettes directly from Lospec."], ["tags", "Palettes"], ["thumbnail", "https://github.com/Variable-ind/Lospec-Palette-Importer/assets/77773850/7ac86623-c428-4409-8f81-c7406527126f"], ["download_link", "https://github.com/OverloadedOrama/Lospec-Palette-Importer/releases/download/v1.1/LospecPaletteImporter.pck"]]
[["name", "OpenDyslexicFont"], ["version", 1.0], ["description", "A Pixelorama extension that sets the OpenDyslexic font as the main font of the user interface."], ["tags", "Fonts"], ["download_link", "https://github.com/OverloadedOrama/OpenDyslexic-Pixelorama-Extension/releases/download/v1.0/OpenDyslexicFont.pck"]]


## Other store links:
### VariableStore
https://raw.githubusercontent.com/Variable-ind/Pixelorama-Extensions/4.0/store_info.md
