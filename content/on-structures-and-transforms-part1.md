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
  tags = ["cat-th"]    
  categories = ["theory"]

# Your own data.
[extra]
# math=true
+++

Patterns are powerful, and luckyly as humans we are quite good at recognizing them. Patters help us
identify things we already know, but the fascinating part is that they help us make predictions about
the unknown. The second one is the fascinating part. We use it all the time. Predicting what someone
might mean from their facial expression when you do not understand the language. We have all had this
experience when we visit a foreign country. Predicting the product of an organic reaction based on
others we have seen before. This is also how we try to debug a looming problem at work. We try to dr-
aw parallel to something we have seen before, to predict the behavior of what's in front of us. The
fundamental the pattern, or theory, the more application of it we will find.

Such a fundamental theory in mathematics is Set Theory. It is so fundametal that when the Logicians
set out to express the entiriety of mathematics in logic, they relied on it. But in here, we will
discuss something else that is equally fundamental if not more so - *Category Theory*. Being one of
those fundamental theories, it has found applications in Psychology, Quantum Mechanics, Control
Theory, and for our purpose, Computer Science.

Category Theory might be a totally alien concept for you as it used to be for me, a few weeks back.
In the upcoming multi-part blog posts, I would like to explore Category Theory with you. But before
we go there, in this post, I would like to lay the structure of how the content will be organized.

I feel that there are three stages to learning a new concept and then becoming proficient in it. The
stages are
- survey
- recognition
- using

The ** Survey ** stage is about starting to know the domain. Here, you go over introductory material
about your topic of choice. The mode of consumption can be blogs, short write ups, books and published
survey papers. I preference is usually books or survey papers. In case I have not come accross any,
I will search the internet to see if people have recommendations of books on the topic. I love buying
books and therefore, if too many people have recommended a book or two, then I will buy them and devour
them. Then usually those books will refer to other books or seminal papers on the topic, and I will
follow the trail. On the first reading of the book, the goal is not to understand everything, in fact
the goal is to only skim the material to know what the experts talk about when they talk about it.
I am just looking to remember the keywords if anything. Once I have gone over 4 or 5 books on the topic,
I am starting to pick favorites. For the second readin, I will pick the book that appealed to me the
most and read it cover to cover. The goal is to get 60 to 70 percent of the material. Remember the 
keywords we noted during the skimming phase, some of them should staring making sense now. The goal
is to have a soliloquy explaining some of the terms or the keywords. I will do the same with the
other books, go over them. Authors have different writing styles and each treat the subject matter
a little differently. No one book is better than all others, just different. Therefore, you must read
more than one text on the topic as each will provide a slightly different intuition than all others.

The first blog will be dedicated to survey. We will go over the fundamental concepts in category theory
and I will try to provide you analogies for each of them. I will skip the maths but instead I will refer
you to books that I think have done an excellent job at that.

Once the things start making sense to you, it is time to train your eyes to see it all around you.
This can take some time and I would argue that we should always keep doing this. One can never get
too good at it. This is also hard and can be frustrating at times. The posts targed to aid in this
endevour, will contain examples and applications of category theory in type theory, language design,
reasoning about concurrency. We will also touch on some applications in Control Theory and Quantum
Mechanics for completeness. We will discuss some seminal papers that introduced this concept in 
Computer Science and also some papers from the recent research.



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

