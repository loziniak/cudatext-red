# [Red][1] integration for [CudaText][2]

## Features

* Syntax coloring
* Custom `nonword_chars`, enables selection of *kebab-case-words* or *types\!* with double click, and for plugins like *Highlight Occurences*
* [Red Language Server][3] integration

## Instructions

1. Clone this repo
1. Copy all files in `data` and `settings` folders to respective subfolders of [CudaText's config folder][4]
1. Install *LSP_Client* plugin
1. Clone [Red Language Server][3] repo
1. Fix paths in `settings/lsp_red.json` and `redlangserver.sh`
1. Restart CudaText

[1]: http://www.red-lang.org/
[2]: https://cudatext.github.io/
[3]: https://github.com/bitbegin/redlangserver
[4]: https://wiki.freepascal.org/CudaText#Location_of_folders_.27settings.27.2C_.27py.27.2C_.27data.27
