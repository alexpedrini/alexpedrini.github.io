---
title: "Publications"
layout: archive
classes: wide
sitemap: true
permalink: /publications/
author_profile: true
---

<p>A full and up-to-date list of my publications and collaborations is available on
<a href="https://ui.adsabs.harvard.edu/search/fl=identifier%2C%5Bcitations%5D%2Cabstract%2Cauthor%2Cbook_author%2Corcid_pub%2Cpublisher%2Corcid_user%2Corcid_other%2Cbibcode%2Ccitation_count%2Ccomment%2Cdoi%2Cid%2Ckeyword%2Cpage%2Cproperty%2Cpub%2Cpub_raw%2Cpubdate%2Cpubnote%2Cread_count%2Ctitle%2Cvolume%2Cdatabase%2Clinks_data%2Cesources%2Cdata%2Ccitation_count_norm%2Cemail%2Cdoctype&fq=%7B!type%3Daqp%20v%3D%24fq_database%7D&fq_database=(database%3Aastronomy%20OR%20database%3Aphysics)&q=orcid%3A0000-0002-8222-8986&rows=25&sort=date%20desc%2C%20bibcode%20desc&start=0&p_=0" target="_blank" rel="noopener">NASA/ADS</a>.</p>

<h2 id="thesis">PhD Thesis</h2>
<div class="pub-list">
{% for pub in site.data.publications.thesis %}{% include publication-card.html pub=pub %}{% endfor %}
</div>

<h2 id="first-author">First-author papers</h2>
<div class="pub-list">
{% for pub in site.data.publications.first_author %}{% include publication-card.html pub=pub %}{% endfor %}
</div>

{% if site.data.publications.co_author and site.data.publications.co_author.size > 0 %}
<h2 id="co-author">Selected co-authored papers</h2>
<div class="pub-list">
{% for pub in site.data.publications.co_author %}{% include publication-card.html pub=pub %}{% endfor %}
</div>
{% endif %}
