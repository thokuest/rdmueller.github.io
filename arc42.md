---
layout: default
---

<p>ein test</p>

{% assign formats = "asciidoc|docbook|docx|epub|html|markdown|markdownMP|textile" | split: "|"  %}  
{% assign types = "plain|withhelp" | split: "|"  %}  
| Format | Language | Plain | With Help |
|--------|----------|-------|-----------|
{% for format in formats %}| {{ format }} | EN | {% for type in types %} [.zip](download/arc42-template-EN-{{type}}-{{format}}.zip?raw=true) |{% endfor %}
|  | DE | {% for type in types %} [.zip](download/arc42-template-DE-{{type}}-{{format}}.zip?raw=true) |{% endfor %}
{% endfor %}
| Confluence 5.x or 6.x | EN | - | [.zip](https://dl.dropboxusercontent.com/u/45486/arc42-downloads/confluence/templateEN-V6-confluence-53.xml.zip) |
| Confluence 4.3 | EN | - | [.zip](https://dl.dropbox.com/u/45486/arc42-downloads/confluence/templateEN-V6-confluence-43.xml.zip) |
| Confluence 4.2 | EN | - | [.zip](https://dl.dropbox.com/u/45486/arc42-downloads/confluence/templateEN-221927-74.xml.zip) |
| Confluence 5.x oder 6.x | DE | - | [.zip](https://dl.dropboxusercontent.com/u/45486/arc42-downloads/confluence/templateDE-V6-confluence-53.xml.zip) | 
| Confluence 4.3 | DE | - | [.zip](https://dl.dropbox.com/u/45486/arc42-downloads/confluence/templateDE-V6-confluence-43.xml.zip) |
| Confluence 4.2 | DE | - | [.zip](https://dl.dropbox.com/u/45486/arc42-downloads/confluence/templateDE-222302-76.xml.zip) |

test

a table?
========

| col1 | col2 |
| ---- | ---- |
| row1 | row1 |
| row2 | row2 |

sdf


| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

