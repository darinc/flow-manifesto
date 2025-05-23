---
layout: default
title: Work Anti-Patterns
---

# Your Work Anti-Pattern Is

*A handy reference for identifying the organizational dysfunctions that destroy flow, autonomy, and joy at work*

---

<div class="anti-pattern-container">
{% for pattern in site.data.anti-patterns %}
<div class="anti-pattern-card">
    <h2><span class="emoji">{{ pattern.emoji }}</span> {{ pattern.title }}</h2>
    <p><strong>What it looks like:</strong> {{ pattern.what_it_looks_like }}</p>
    <p><strong>Why it's wrong:</strong> {{ pattern.why_its_wrong }}</p>
    <p><strong>The better way:</strong> {{ pattern.the_better_way }}</p>
</div>
{% endfor %}
</div>

---

*When you spot these patterns, you've identified opportunities to improve how work gets done. The goal isn't to shame people but to name the dysfunctions so we can address them systematically.*

[← Back to Flow Manifesto](index.md)

