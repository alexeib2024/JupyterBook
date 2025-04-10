# My Sample Jupyter Book

This is a sample Jupyter Book project that demonstrates various content types and features. The book includes examples of markdown files, Jupyter notebooks, and MyST Markdown.

## Project Structure

- `intro.md` - Welcome page and book introduction
- `markdown.md` - Examples of basic Markdown and MyST syntax
- `notebooks.ipynb` - Sample Jupyter notebook with code examples
- `markdown-notebooks.md` - Demonstration of MyST Markdown notebooks
- `mymarkdown.md` - Custom markdown content with cross-references
- `_config.yml` - Book configuration settings
- `_toc.yml` - Table of contents structure
- `references.bib` - Bibliography file for citations

## Requirements

The following Python packages are required:

```
jupyter-book
matplotlib
numpy
```

## Building the Book

To build the book:

1. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```

2. Build the book:
   ```bash
   jupyter-book build .
   ```

The built book will be available in the `_build/html` directory.

## Features Demonstrated

- Basic Markdown formatting
- Code cells and outputs
- Math equations
- Citations and references
- Cross-references between pages
- Interactive plots with Matplotlib
- MyST Markdown notebooks
- Custom table of contents

## License

This project uses content from the Jupyter Book Community. For more information about Jupyter Book, visit [jupyterbook.org](https://jupyterbook.org).
