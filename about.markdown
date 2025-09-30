---
layout: page
title: About
permalink: /about/
---

Home River Media grew out of a personal fight for Sámi rights — and has since become a home for diverse Sámi stories. From intimate documentaries to bold comedies and playful animations, we are building a slate that is small but growing fast. What unites our work is the belief that film is a tool for change, and that Sámi voices belong at the centre. Our mission is simple: to add richness to Sámi cinema and to make sure our stories are told by us, not just about us.

<div class="grid-container">
    {%- for profile in site.profiles -%}
    <div class="grid-card">
    {%- if profile.image -%}
        <img src="{{ profile.image | relative_url }}" alt="{{ profile.name | escape }}">
    {%- endif -%}
    <h2>{{ profile.name | escape }}</h2>
    <div class="grid-text">
        <div>Home River Media was founded by producer and activist Kati Eriksen after her debut film Home River (2023), a short documentary about the Sámi people’s constitutional right to fish in their river. The experience revealed the potential of film as a tool for change and inspired the creation of the company.</div>
        <br>
        <div>With a background in Sámi rights advocacy and cross-border cultural projects, Eriksen combines political experience with a passion for filmmaking. She is committed to creating space for Sámi voices and to supporting both emerging and established filmmakers across genres and Sámi languages. Project management and financing are her particular strengths — she brings structure, strategy, and the ability to secure resources for Sámi-led film production.</div>
    </div>
    </div>
    {%- endfor -%}
</div>