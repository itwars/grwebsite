+++
# Projects widget.
# This widget displays all projects from `content/project/`.
widget = "projects"
active = true
date = "2016-04-20T00:00:00"
folder = "project"
title = "Projects"
#subtitle = "Things I am working on or have created"

# Order that this section will appear in.
weight = 10

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards, 2 = showcase.
view = 2

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
filter_default = 0

# Add or remove as many filters (`[[filter]]` instances) as you like.
# Use "*" tag to show all projects or an existing tag prefixed with "." to filter by specific tag.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.
[[filter]]
  name = "All"
  tag = "*"

[[filter]]
  name = "Data Science"
  tag = "data"

[[filter]]
  name = "Writing"
  tag = "pol"

[[filter]]
  name = "Amateur Radio"
  tag = "radio"
+++
