---
layout: home
---

# Soliloque

Hiver deux mille je sais pas combien ; c'était avant le COVID. La fin d'année a cette odeur bleue qui fout des larmes quand on respire trop fort. Plus rien ne m'intéresse au travail.
J'ai alors cet élan qui nous traverse tous lorsque le compteur de l'année repasse à zéro ; ça me frappe violemment, je dois agir et vite.

Je vais bosser sur un jeu.

Au fond de moi je savais bien que je n'irais pas. Qu'écrire est trop long, et trop douloureux. Que je pars de presque rien sur le plan technique. Donc, je n'ai jamais honoré la promesse que je m'étais faite.

Puis vient juillet 2025. En fait, j'ai bossé. En fait, j'ai un jeu simple, une belle histoire à raconter, que je mâche et digère en boucle depuis tout ce temps. Sur le mur sous mes yeux, j'ai collé des post its. Ce sont les points centraux de l'histoire. Ils prennent la poussière car je suis lent. Mais j'y pense.
Et l'écriture est douloureuse.
Et Unity est insupportable (ou plutôt je ne connais pas assez).
Et j'ai encore mille millions de questions.

Mais je mets tout ça à la poubelle.
Saltwater va sortir.

De toute façon c'est ça ou je vais à la plage et je nage dans la mer jusqu'à couler.

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
