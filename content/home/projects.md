+++
# Projects widget.
widget = "projects"
active = true
date = "2016-04-20T00:00:00"

title = "Projects"
subtitle = "Corporate & Personal projects"

# Order that this section will appear in.
weight = 50

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
folder = "project"

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards.
view = 1

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
filter_default = 0

# Add or remove as many filters (`[[filter]]` instances) as you like.
# Use "*" tag to show all projects or an existing tag prefixed with "." to filter by specific tag.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.
# [[filter]]
#   name = "All"
#   tag = "*"

[[filter]]
  name = "Archive"
  tag = ".Archive"

[[filter]]
  name = "Language Documentation"
   tag = ".Language-Documentation"

[[filter]]
 name = "Architecture"
 tag = ".Architecture"

#[[filter]]
#  name = "Text Input"
#  tag = ".typing"

[[filter]]
  name = "Orthographies"
  tag = ".Orthographies"

[[filter]]
  name = "User Experience"
  tag = ".UX"
+++
