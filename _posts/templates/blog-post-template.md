<%* 
let title = await tp.system.prompt("Please enter the post's title.")
 cleanTitle = title.replace(/ /g, "-").replace(/[^a-zA-Z0-9-_]/g, '').toLowerCase()
  fileName = tp.date.now("YYYY-MM-DD") + "-" + cleanTitle
 await tp.file.rename(fileName) 
-%>
---
title: <% title %>
SEO_title:
slug: /<% cleanTitle %>/
excerpt: 
featured_image: 
redirect_from: 
---