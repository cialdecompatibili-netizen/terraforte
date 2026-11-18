---
layout: single
title: "Servizi"
permalink: /servizi/
ref: servizi
author_profile: false
seo_description: "Scavi, movimento terra, escavatori, miniescavatori, camion e trattori per terreni: il mezzo giusto per ogni lavoro."
classes: wide
---

Scavi, movimento terra, trasporti con camion e lavori sui terreni, con il mezzo adatto a ogni lavoro.

<div class="grid__wrapper">
{% assign svc = site.servizi | sort: "ordine" %}{% for item in svc %}<div class="grid__item"><article class="archive__item"><h2 class="archive__item-title no_toc"><a href="{{ item.url | relative_url }}" rel="permalink">{{ item.title }}</a></h2><p class="archive__item-excerpt">{{ item.description | strip_html | truncate: 160 }}</p></article></div>
{% endfor %}</div>

## Come si svolge un incarico
1. **Ci racconti il lavoro**: dove, quanto è grande, che terreno è.
2. **Scegliamo i mezzi**: escavatore, miniescavatore, camion o trattore.
3. **Preventivo**: costi e tempi prima di iniziare.
4. **Lavoro e pulizia**: l'area resta in ordine.

[Chiedi un preventivo]({{ '/contatti/' | relative_url }}){: .btn .btn--primary}
