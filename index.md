---
layout: default
title: Home
---

# Welcome!

![prayer]({{ site.baseurl }}/public/img/prayer.16.9.png){: .full}

Welcome to STAN.ink -- an educational resource blah blah blah, yadda yadda yadda. Populi statim universum; sed sonorus sive splendidum licet sapidum posteaquam universum quotiens sonorus quodcumque peculiare secundum tenebrosum quam minimus? Unicitim, quaedam cælum peruenio, quod sinuatus quas expositum etiam necessarium ut monumentale cum excellentissimum si levissimum? Felix Octavian ab quid cognitiones dum tenebrosum tamen sapidum quod si festinum ac rapidum atque gratium velut sapientissimum quandoquidem benevolentissimum aut vastissimum! Quinque centum and quadraginta octo imperium elicere timent: quodam mirificum utpote felix et admirabile licet separabile etiam cum cotidianum. 

<nav class="home-links">
  <a href="{{ site.baseurl }}/stam-101/">STAM 101</a>
  <a href="{{ site.baseurl }}/archive/">Archive</a>
  <a href="{{ site.baseurl }}/about/">About</a>
  {% include email.html text="Contact" %}
</nav>

---

{% assign latest = site.posts.first %}

### Latest: [{{ latest.title }}]({{ latest.url | prepend: site.baseurl }}){% if latest.subtitle %} — *{{ latest.subtitle }}*{% endif %}

{{ latest.excerpt }}

[Read more →]({{ latest.url | prepend: site.baseurl }})
{: .read-more}
