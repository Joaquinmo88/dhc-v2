---
layout: detail_caso_exito
permalink: /santa-ines/
image: santa-ines.jpg
title: "Santa Inés"
description: "Restauración de la torre y fachada de la iglesia de Santa Inés Texcoco, Estado de México..."
---

<div class="container-fluid mt-3 pb-3">
    <div class="container bg-white">
        <div class="p-5 ">
            <h1 class="cnt-title">{{page.title}}</h1>
             <p>
                Para el equipo de DHC ha sido un honor poder reconstruir y rehabilitar la torre y fachada de la iglesia de Santa Inés Texcoco, Estado de México conservando la naturalidad y los detalles arquitectónicos con los que cuenta por el gran valor que representa debido a su antigüedad.
            </p>
            <p class="text-inportant-resalt">
                <em>Todo el trabajo realizado a la iglesia fue con material 100% natural.</em>
            </p>
        </div>
        <div id="gallery" class="container-gallery">
            {% for i in (1..13) %}
            <img alt="{{page.title}}" src="/assets/images/gallerys/santa-ines/thumbnail/{{i}}.jpg"
                data-image="/assets/images/gallerys/santa-ines/{{i}}.jpg" data-description="{{page.title}}">
            {% endfor %}
        </div>
    </div>
</div>