---
layout: default
---
{% assign formats = "asciidoc|docbook|docx|epub|html|markdown|markdownMP|textile" | split: "|"  %}  
{% assign types = "plain|withhelp" | split: "|"  %}  
| Format | Language | Plain | With Help |
|--------|----------|-------|-----------|
{% for format in formats %}| {{ format }} | EN | {% for type in types %} [.zip](download/arc42-template-EN-{{type}}-{{format}}.zip?raw=true) |{% endfor %}
|  | DE | {% for type in types %} [.zip](download/arc42-template-DE-{{type}}-{{format}}.zip?raw=true) |{% endfor %}
{% endfor %}| Confluence | EN |  | [5.x or 6.x](https://dl.dropboxusercontent.com/u/45486/arc42-downloads/confluence/templateEN-V6-confluence-53.xml.zip), [4.3](https://dl.dropbox.com/u/45486/arc42-downloads/confluence/templateEN-V6-confluence-43.xml.zip), [4.2](https://dl.dropbox.com/u/45486/arc42-downloads/confluence/templateEN-221927-74.xml.zip) |
|  | DE |  | [5.x oder 6.x](https://dl.dropboxusercontent.com/u/45486/arc42-downloads/confluence/templateDE-V6-confluence-53.xml.zip), [4.3](https://dl.dropbox.com/u/45486/arc42-downloads/confluence/templateDE-V6-confluence-43.xml.zip), [4.2](https://dl.dropbox.com/u/45486/arc42-downloads/confluence/templateDE-222302-76.xml.zip) |
----

test
