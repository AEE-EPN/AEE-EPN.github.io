---
layout: home
---
# ¡Bienvenidos al Tablero de Noticias!

Este es el espacio oficial de la Asociación. Aquí publicaremos todos los comunicados importantes, convocatorias y avisos para mantener a nuestra comunidad siempre informada.

---

## 📢 Últimos Anuncios

<ul>
  {% for post in site.posts %}
    <li style="margin-bottom: 10px;">
      <strong>{{ post.date | date: "%d/%m/%Y" }}</strong> &raquo; 
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
