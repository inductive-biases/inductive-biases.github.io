---
layout: default
menu: ["Workshop","Abstract","Speakers","Key Dates","Call for Papers","Schedule"]
---

<div id="workshop" class="bg-light">
<div class="container text-center py-5">
<img alt="NeurIPS" src='data:image/svg+xml;utf8,{% include_relative neurips.svg %}'>
<h1 class="py-5">Interpretable Inductive Biases<br>and Physically Structured Learning</h1>
</div>
</div>

<div id="abstract" class="container py-4">
{% capture abstract %}{% include_relative abstract.md %}{% endcapture %}
{{ abstract | remove_first: "---" | remove_first: "published: false" | remove_first: "---" | markdownify }}
</div>

<div class="bg-light">
<div id="speakers" class="container py-4">
{% capture speakers %}{% include_relative speakers.html %}{% endcapture %}
{{ speakers | remove_first: "---" | remove_first: "published: false" | remove_first: "---" }}
</div>
</div>


<div id="keydates" class="container py-4">
{% capture keydates %}{% include_relative keydates.md %}{% endcapture %}
{{ keydates | remove_first: "---" | remove_first: "published: false" | remove_first: "---" | markdownify }}
</div>

<div class="bg-light">
<div id="callforpapers" class="container py-4">
{% capture callforpapers %}{% include_relative callforpapers.md %}{% endcapture %}
{{ callforpapers | remove_first: "---" | remove_first: "published: false" | remove_first: "---" | markdownify }}
</div>
</div>


<div id="schedule" class="container py-4">
{% capture schedule %}{% include_relative schedule.md %}{% endcapture %}
{{ schedule | remove_first: "---" | remove_first: "published: false" | remove_first: "---" | markdownify }}
</div>

<div class="bg-light">
<div class="container py-4">
{% capture organizers %}{% include_relative organizers.html %}{% endcapture %}
{{ organizers | remove_first: "---" | remove_first: "published: false" | remove_first: "---" }}
</div>
</div>


<div class="container py-4">
{% capture advisory %}{% include_relative advisory.html %}{% endcapture %}
{{ advisory | remove_first: "---" | remove_first: "published: false" | remove_first: "---" }}
</div>