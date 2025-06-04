---
title: "Publications"
type: "landing"   # Blox 테마에서 Publications를 렌더링하는 레이아웃을 지정(테마마다 다를 수 있음).

[cascade]
  [[cascade.sections]]
    block = "collection"
    id = "journals-all"
    [cascade.sections.content]
      title = "Journal Articles"
      folders = ["publication/journal-article"]
      publication_type = "article-journal"
      count = 0
      sort_by = "Date"
      sort_ascending = false
    [cascade.sections.design]
      view = "compact"

  [[cascade.sections]]
    block = "collection"
    id = "conference-all"
    [cascade.sections.content]
      title = "Conference Papers"
      folders = ["publication/conference-paper"]
      publication_type = "conference-paper"
      count = 0
      sort_by = "Date"
      sort_ascending = false
    [cascade.sections.design]
      view = "compact"

  [[cascade.sections]]
    block = "collection"
    id = "preprint-all"
    [cascade.sections.content]
      title = "Preprints"
      folders = ["publication/preprint"]
      publication_type = "preprint"
      count = 0
      sort_by = "Date"
      sort_ascending = false
    [cascade.sections.design]
      view = "compact"
---

<!-- 
---
title: Publications
cms_exclude: true

# View.
view: citation

# Optional header image (relative to `static/media/` folder).
banner:
  caption: ''
  image: ''
--- -->
