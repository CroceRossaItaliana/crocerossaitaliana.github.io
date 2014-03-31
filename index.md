---
layout: page
title: FAQ di Gaia
tagline: Croce Rossa Italiana
---

Questo sito web raccoglie le domande che vengono poste pi&ugrave; di frequente alla Squadra di supporto di Gaia.

Vuole essere una risorsa sia per gli Utenti che per la nostra Squadra di Supporto di Primo Livello.

### FAQ presenti

<ul class="posts">
  {% for post in site.posts %}
    <li>(<span>{{ post.date | date_to_string }}</span>) <strong><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></strong></li>
  {% endfor %}
</ul>

### Non &egrave; ancora chiaro...

Se non hai trovato la risposta alla tua domanda su questo sito, oppure qualcosa non &egrave; esaustivo, ti preghiamo di contattarci [all'indirizzo email supporto@gaia.cri.it](mailto:supporto@gaia.cri.it).
