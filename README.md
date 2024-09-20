# Deprecated ⚠️
Moved to: https://github.com/saritasa-nest/usummit-html-docx

# HTML-DOCX

A tool for conversion of HTML to docx formatted content

## Example

```python
from html_docx import add_html
from docx import Document


html_content = '<h1>Example</h1><p><b>Bold</b> or Normal</p>'
document = Document()
document = add_html(document, html_content)
document.save('example.docx')
```
