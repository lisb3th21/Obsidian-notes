<%"---"%>
creation date: <% tp.file.creation_date() %>
modification date: <% tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
tag: book 
title: "{title}"
author: [{{author}}]
publish: {{publishDate}}
cover: {{coverUrl}}
status: #book/unread
end date: 01/01/01
format: #format/digital
stars: #⭐⭐⭐⭐⭐
<%"---"%>

![cover|150]({{coverUrl}}) 
# {{title}}

|           |            |
| --------- | ---------- |
| Formato   | {{format}} |
| Páginas   |            |
| Género    |            |
| Estrellas | {{stars}}  |
| Estado    | {{status}} |
- Personaje favorito: 
- Personaje odiado:
## Review
