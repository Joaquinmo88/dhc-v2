---
layout: detail_caso_exito
permalink: /papalotla/
image: papalotla.jpg
title: "Papalotla"
description: "Restauración de la cúpula y torre de la iglesia de Papalotla, Estado de México..."
---

<div class="container-fluid mt-3 pb-3">
    <div class="container bg-white">
        <div class="p-5 ">
            <h1 class="cnt-title">{{page.title}}</h1>
            <p>
                Para el equipo de DHC ha sido un honor poder reconstruir y rehabilitar la cúpula y torre de la iglesia de Papalotla, Estado de México conservando la naturalidad y los detalles arquitectónicos con los que cuenta por el gran valor que representa debido a su antigüedad.
            </p>
            <p class="text-inportant-resalt">
                <em>Todo el trabajo realizado a la iglesia fue con material 100% natural.</em>
            </p>
        </div>
        <div id="gallery" class="container-gallery">
            {% for i in (1..53) %}
            <img alt="{{page.title}}" src="/assets/images/gallerys/papalotla/etapa-exterior/thumbnail/{{i}}.jpg"
                data-image="/assets/images/gallerys/papalotla/etapa-exterior/{{i}}.jpg" data-description="{{page.title}}">
            {% endfor %}
        </div>
        <h2 class="separador-gallery"><span>Interior</span></h2>
        <div id="gallery-1" class="container-gallery">
            {% for i in (1..100) %}
            <img alt="{{page.title}}" src="/assets/images/gallerys/papalotla/etapa-interior/thumbnail/{{i}}.jpg"
                data-image="/assets/images/gallerys/papalotla/etapa-interior/{{i}}.jpg" data-description="{{page.title}}">
            {% endfor %}
        </div>
    </div>
</div>