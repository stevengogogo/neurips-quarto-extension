# Use of the NeurIPS format template

This is a [Quarto-based](https://quarto.org) template that assists you in creating a manuscript for Computo.

## Creating a new article

You can use this as a template to create an article for Computo. To do this, use the following command:

```bash
quarto use template stevengogogo/neurips-quarto-extension
```

This will install the extension and create an example qmd file and bibiography that you can use as a starting place for your article.

## Installation for existing document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```bash
quarto add stevengogogo/neurips-quarto-extension
```

## Installation for side packages

1. [TinyLatex](https://quarto.org/docs/output-formats/pdf-engine.html)
   ```bash
   quarto install tinytex --update-path
   ```
1. [dviscgm](https://dvisvgm.de/Downloads/)
1. [R installabion with Conda](https://docs.anaconda.com/free/working-with-conda/packages/using-r-language/)
1. [R package installation](https://www.geeksforgeeks.org/how-to-install-a-package-in-r/)
  - This is required when R package is missing in the environment
1. [Required python pakcage](environment.yml)

## Usage

To use the format, you can use the format names `computo-html`. For example:

```bash
quarto render article.qmd --to neurips-html
```

or in your document yaml

```yaml
format:
  neurips-html: default
```

You can view a preview of the rendered HTML and PDF template at <https://computorg.github.io/computo-quarto-extension/> (for PDF, see "other formats" bnext to the TOC).


## Example

- PDF output is at https://stevengogogo.github.io/neurips-quarto-extension/template.pdf
- HTML: https://stevengogogo.github.io/neurips-quarto-extension/