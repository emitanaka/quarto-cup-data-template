
# Quarto template for CUP Data Template

## Creating a New Article

To create a new article using this format:


```bash
quarto use template emitanaka/quarto-cup-data-template
```

This will create a new directory with an example document that uses this format.

## Using with an Existing Document

To add this format to an existing document:

```bash
quarto add emitanaka/quarto-cup-data-template
```

Then, add the format to your document options:

```yaml
format:
  cup-data-pdf: default
```    


## Example

Here is the source code for a minimal sample document: [template.qmd](template.qmd).

