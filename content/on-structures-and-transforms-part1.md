+++
title = "On Structures and Transforms"
description = ""

# The date of the post.
# Two formats are allowed: YYYY-MM-DD (2012-10-02) and RFC3339 (2002-10-02T15:00:00Z).
# Do not wrap dates in quotes; the line below only indicates that there is no default date.
# If the section variable `sort_by` is set to `date`, then any page that lacks a `date`
# will not be rendered.
# Setting this overrides a date set in the filename.
date = 2023-01-03

# The last updated date of the post, if different from the date.
# Same format as `date`.
updated = 2023-01-03

# A draft page is only loaded if the `--drafts` flag is passed to `zola build`, `zola serve` or `zola check`.
draft = true

# When set to "true", the page will be in the search index. This is only used if
# `build_search_index` is set to "true" in the Zola configuration and the parent section
# hasn't set `in_search_index` to "false" in its front matter.
in_search_index = true

# Template to use to render this page.
template = "page.html"

# The taxonomies for this page. The keys need to be the same as the taxonomy
# names configured in `config.toml` and the values are an array of String objects. For example,
# tags = ["rust", "web"].
[taxonomies]
  tags = ["concepts", "cat-th"]    
  categories = ["theory"]

# Your own data.
[extra]
+++



<script src="https://giscus.app/client.js"
        data-repo="distributed-randomness/distributed-randomness.github.io"
        data-repo-id="MDEwOlJlcG9zaXRvcnkzMTA0ODM4MDg="
        data-category="General"
        data-category-id="DIC_kwDOEoGbYM4CTI7I"
        data-mapping="pathname"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-input-position="top"
        data-theme="dark_high_contrast"
        data-lang="en"
        crossorigin="anonymous"
        async>
</script>

