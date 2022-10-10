# csl-to-markdown

Makes Zotero's bibliography export compatible with markdown

## Folk details

This folk reverts to previous 0.10 release as I couldn't get 0.2.0 to work. The italic markdown has been modified to use a single asterisk (\*) as I prefer this.

## Requirements
You need to install Rust [see](https://www.rust-lang.org/en-US/install.html) to test and build this code.

## Test

On unix based system :

```bash
cargo test
```

## Build

```bash
cargo build --release
```

## Usage

1- Make your csl file compatible with markdown. See the full list of styles [here](https://www.zotero.org/styles).

**On unix based system :**
```bash
./csl_to_markdown input_file.csl > output_file.csl
```

2- Add this new style to Zotero. [See how to install a citation style](https://www.zotero.org/support/styles#alternative_installation_methods) from a file.

3- Use this new style to [create a bibliography](https://www.zotero.org/support/creating_bibliographies) compatible with markdown. Dont forget to select the good citation style before exporting your bibliography.

## Acknowledgement

This software is inspired by this blog article : ["Markdown et Zotero"](https://zotero.hypotheses.org/2258#autres_usages)

## Licence

This software is distributed under the MIT licence.
