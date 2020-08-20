---
layout: default
menu: ["Workshop","Abstract","Speakers","Key Dates","Call for Papers","Schedule"]
---

<div id="workshop" class="bg-light">
<div class="container text-center py-5">
{% capture logo %}{% include_relative neurips.svg %}{% endcapture %}
{% assign left_brace = "{" %}
{% assign right_brace = "}" %}
<img alt="NeurIPS" src='data:image/svg+xml,{{ logo | replace: "<","%3C" | replace: ">","%3E" | replace: " ","%20" | replace: "#","%23" | replace: left_brace,"%7B" | replace: right_brace,"%7D" }}'>
<h1 class="my-5">
<span class="h3">NeurIPS workshop on</span>
<br>
Interpretable Inductive Biases<br>and Physically Structured Learning
</h1>
<h2 class="h4 my-4">December 11<sup>th</sup>–12<sup>th</sup>, 2020</h2>
</div>
</div>


<div class="bg-white">
<div id="abstract" class="container py-4">
{% capture abstract %}{% include_relative abstract.md %}{% endcapture %}
{{ abstract | remove_first: "---" | remove_first: "published: false" | remove_first: "---" | markdownify }}
</div>
</div>


<div class="bg-light">
<div id="speakers" class="container py-4">
{% capture speakers %}{% include_relative speakers.html %}{% endcapture %}
{{ speakers | remove_first: "---" | remove_first: "published: false" | remove_first: "---" }}
</div>
</div>


<div class="bg-white">
<div id="callforpapers" class="container py-4">
{% capture callforpapers %}{% include_relative callforpapers.md %}{% endcapture %}
{{ callforpapers | remove_first: "---" | remove_first: "published: false" | remove_first: "---" | markdownify }}
</div>
</div>


<div class="bg-light">
<div id="keydates" class="container py-4">
{% capture keydates %}{% include_relative keydates.md %}{% endcapture %}
{{ keydates | remove_first: "---" | remove_first: "published: false" | remove_first: "---" | markdownify }}
</div>
</div>


<div class="bg-white">
<div class="container py-4">
{% capture organizers %}{% include_relative organizers.html %}{% endcapture %}
{{ organizers | remove_first: "---" | remove_first: "published: false" | remove_first: "---" }}
</div>
</div>


<div class="bg-light">
<div class="container py-4">
{% capture advisory %}{% include_relative advisory.html %}{% endcapture %}
{{ advisory | remove_first: "---" | remove_first: "published: false" | remove_first: "---" }}
</div>
</div>