---
layout: default
---

# Nouvel an, nouvelle ère

Hiver deux mille je sais pas combien ; c'était avant le COVID. Plus rien ne m'intéresse vraiment, je m'ennuie.
J'ai alors cet élan qui nous traverse tous lorsque le compteur de l'année repasse à zéro ; ça me frappe violemment, une _bonne résolution_ : je **dois** bosser sur un jeu.

Au fond de moi je sais bien que cette impulsion de mènera pas à grand chose. Parce qu'écrire est trop long, et trop douloureux. Parce qu'il me manque toutes les connaissances techniques, ou presque. Et comme attendu, je n'honore pas la promesse que je me suis faite.

Puis vient juillet 2025. Et je me rends compte... En fait, j'ai bossé.
En fait, j'ai une idée simple, une belle histoire à raconter, que je mâche et digère en boucle depuis tout ce temps. J'ai des post-its sur les murs. Qu'est-ce qui me bloque, **vraiment** ?
Oui, l'écriture est douloureuse.
Oui, je suis perdu sur Unity.
Oui, il me reste des millions de questions.

Mais tout ça, c'est rien.
Saltwater va sortir.

_C'est ma lueur à l'horizon._

---

## Derniers billets

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <span class="post-meta">{{ post.date | date: "%d %b %Y" }}</span>
      <h3>
        <a class="post-link" href="{{ post.url | relative_url }}">
          {{ post.title | escape }}
        </a>
      </h3>
      {% if post.excerpt %}
        {{ post.excerpt }}
      {% endif %}
    </li>
  {% endfor %}
</ul>

<p><a href="{{ "/posts/" | relative_url }}">Voir tous les billets →</a></p>
