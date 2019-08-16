---
layout: detail_caso_exito
permalink: /san-pedro-chiautzingo/
image: san-pedro-chiautzingo.jpg
title: "San Pedro Chiautzingo"
description: "Restauración de la torre y fachada de la iglesia de San Pedro Chiautzingo, Tepetlaoxtoc, Estado de México..."
---

<section class="bg-white p-0 m-0">
    <div class="container-fluid pt-3 pb-3">
        <div class="p-5 ">
            <h1 class="cnt-title">{{page.title}}</h1>
            <p>
                Para el equipo de DHC ha sido un honor poder reconstruir y rehabilitar la torre y fachada de la iglesia de San Pedro Chiautzingo, Tepetlaoxtoc, Estado de México conservando la naturalidad y los detalles arquitectónicos con los que cuenta por el gran valor que representa debido a su antigüedad.
            </p>
            <p class="text-inportant-resalt">
                <em>Todo el trabajo realizado a la iglesia fue con material 100% natural.</em>
            </p>
        </div>
        <div id="gallery" class="container-gallery">
            {% for i in (1..10) %}
            <img alt="{{page.title}}" src="/assets/images/gallerys/san-pedro-chiautzingo/thumbnail/{{i}}.jpg"
                data-image="/assets/images/gallerys/san-pedro-chiautzingo/{{i}}.jpg" data-description="{{page.title}}">
            {% endfor %}
        </div>
    </div>
</section>