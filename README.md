# nastatement

This is a [Quarto](https://quarto.org/) extension to provide a PDF template for a short statement letter. 

## Installation

If you want to start with a template do:
```bash
quarto use template nareal/nastatement
```

You just want to install the extension use:
```bash
quarto install extension nareal/nastatement
```

This command installs the extensions under the `_extension` subdirectory.

If you want you can specify the version number:
```bash
quarto install extension nareal/nastatement@v1.0
```

To update the extension use:
```bash
quarto update extension nareal/nastatement
```

and to remove it:
```bash
quarto remove extension nareal/nastatement
```

## Usage

You can use the following metadata fields:

```yaml
format: 
  nastatement-pdf:
    title: "To whom it may concern"
    fromname: Author name
    fromtitle: Author title
    fromWWW: https://web.address
    fromemail: email@somewhere.com
    fromphone: +999 999 999
    fromaddress: |
                 | University address
                 | Somewhere
                 | Universe
    closing: Best regards,
    spacing: 1.4
    sansfont: NewsGotT
    lang: en-GB # pt-PT
    babel-lang: british # portuguese
    #date: Thursday, 18 October 2022
    #logofilepath:  um-eeg
    #keep-tex: true
```
