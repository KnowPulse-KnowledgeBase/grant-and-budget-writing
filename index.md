---
layout: lesson
root: .
# Overall title for the Lesson.
# This should be in the form of a question if possible.
title: "How do I write a funding proposal?"

# Single Sentence purpose for this lesson.
short-purpose: "This lesson contains resources related to grant and budget writing."

# Single-Sentence describing the researchers
# who will be helped by this tutorial.
who: "Graduate students, researchers and Post-Doctoral Fellows"

# A comma-separated list of maintainers for this lesson.
maintainers: "Lacey-Anne Sanderson, Ruobin Liu, Laura Jardine"

# A short paragraph describing why we created this lesson.
# What question is it trying to solve and why is that question important.
why: "Writing grants can be a frustrating process and success rates are generally low (commonly 25-35%). However, repeatedly applying for funding is a reality when working within academia. This repository serves as a place where students and researchers can find advice and tools for writing better grant proposals from academics around the world."

# A short list of items researchers will learn in this lesson.
learn:
- "Using the Message Box Workbook to better communicate your work"
- "Writing a grant budget"
- "Writing and budgeting resources"

data-description: "Not applicable to this lesson."
---

The KnowPulse KnowledgeBase focuses on short question-based lessons to help researchers get their work done.

- **Purpose:** {{ page.short-purpose }}
- **Who:** {{ page.who }}
- **Maintainer(s):** {{ page.maintainers }}

{{ page.why }}

<strong>Some of the things you will learn include:</strong>
<ul>
	{% for item in page.learn %}
	<li style="font-weight:bold">{{ item|markdownify }}</li>
	{% endfor %}
</ul>

> ## Getting Started
>
> The KnowPulse KnowledgeBase lessons are hands-on, so participants are
> encouraged to use their own computers to ensure the proper setup of tools
> for an efficient workflow. To most effectively use these materials,
> please make sure to download the data and install everything before
> working through this lesson.
>
> This workshop assumes no prior experience with the tools covered in the
> workshop.
>
> To get started, follow the directions in the [Setup](setup.html) tab to
> get access to the required software and data for this workshop.
{: .prereq}


> ## Data
>
> {{ page.data-description }}
{: .prereq}
