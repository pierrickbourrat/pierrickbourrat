---
title: Publications
cms_exclude: true

# Page type and layout
type: landing
sections:
  - block: markdown
    content:
      title: "Publications"
    design:
      columns: "1"
      spacing:
        padding: ["20px", "0", "0", "0"]  # Reduce bottom padding
      css_class: "pub-title"  # Custom class for styling
  - block: collection
    content:
      title: ""  # Empty to avoid duplicate title (page title is enough)
      text: ""   # Optional intro text if desired
      filters:
        folders:
          - publication  # Source folder for publication content
      count: 0   # Show all items (no pagination limit)
    design:
      view: citation  # Compact view for a clean list
      columns: "1"   # Single column layout
      sort_by: "Date"  # Sort by publication date
      sort_ascending: false  # Reverse order (newest first)
      disable_individual_pages: true  # Prevents individual pages

# Optional banner
banner:
  caption: ''
  image: ''
---