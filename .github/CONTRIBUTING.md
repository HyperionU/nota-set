# How To Contribute
Hello! From all of us at The University of Hyperion, we're so glad you are taking the time to join us.
If you haven't already, consider sending an introduction on the discussion tab, or joining the [Slack Channel](https://join.slack.com/t/newworkspace-pcc1266/shared_invite/zt-2e8wglpe8-HC1ylv~YIeyOxtpeol1Q7g)<sup>1</sup> at the previous link.

<!-- TOC start (generated with https://github.com/derlin/bitdowntoc) -->

- [Submitting Changes](#submitting-changes)
- [Conventions](#conventions)

<!-- TOC end -->

## Submitting Changes
If you are making changes, send a [Pull Request](https://github.com/HyperionU/Nota-Set/compare)<sup>2</sup> at the previous link with a clear list (and / or explanation) of what you've done. [Read More](https://support.github.com/)<sup>3</sup>
When you send one, we will be forever grateful if you also include a web link to the notes. (As a result of the Zero Markdown Project, all sets and requests of notes with Markdown pages after switchover will be denied.)
Please follow general conventions (below) and make sure that all commits are Atomic (one feature / one note per commit).
Always write a clear log message for your commits. One-line messages are fine for small changes, but bigger changes should look like this:
```bash
$ git commit -m "A brief summary of the commit
> 
> A paragraph describing what changed and its impact."
```
If you don't know where to start, look for any issues labeled ![Static Badge](https://img.shields.io/badge/good_first_issue-7057ff), or if you have some experience, look to ![Static Badge](https://img.shields.io/badge/help_wanted-008672) for some easier issues.


## Conventions
If you read some of the sources, you'll get the hang of it. Put simply: Keep it simple, Keep it readable, Keep it idem.
- Same front matter for all notes (below)
```markdown
---
marp: true
theme: uncover
class: invert
paginate: true
math: mathjax
---
```
- ALWAYS put spaces after list items and method parameters (`[1, 2, 3]`, not `[1,2,3]`), around operators (`$x += 1$`, not `$x+=1$`), and around hash arrows.
- Spacing between slide content (below)
```markdown
---

## Title

text
* segmented item
- non-segmented item

---
```
- This is open source software. Consider the people who will read your code, and make it look nice for them. It's sort of like driving a car: Perhaps you love doing donuts when you're alone, but with passengers the goal is to make the ride as smooth as possible.

Finally, if you are confused or unsure about something, ask. Ask either on the Discussions tab or the Slack Channel<sup>1</sup>.\
From all of us here, thanks for making Nota-Set better and more accessible!\
-G. D. (Maintainer of Nota-Set, Founder / President of Hyperion University)
