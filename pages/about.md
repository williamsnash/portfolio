---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
I am a Motivated, hard-working Cyber Security Engineering student at Iowa State University, with tested experience in Python and Java coding, and Bash scripting. I have a strong work ethic, work well in a team environment, very dedicated, and I have strong communication skills.

<details><summary>Click to View Resume</summary>

<iframe src="../assets/W. Nash Resume.pdf" title="description" width="100%" height="700px"></iframe>
</details>

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>