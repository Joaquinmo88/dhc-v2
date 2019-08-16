---
layout: detail_caso_exito
permalink: /san-jeronimo/
image: san-jeronimo.jpg
title: "San Jerónimo"
description: "Restauración de la arcada frontal y lateral de la iglesia de San Jerónimo, Texcoco, Estado de México..."
---

<div class="container-fluid mt-3 pb-3">
    <div class="container bg-white">
        <div class="p-5 ">
            <h1 class="cnt-title">{{page.title}}</h1>
            <p>
                Para el equipo de DHC ha sido un honor poder reconstruir y rehabilitar la arcada frontal y lateral de la iglesia de San Jerónimo, Texcoco, Estado de México conservando la naturalidad y los detalles arquitectónicos con los que cuenta por el gran valor que representa debido a su antigüedad.
            </p>
            <p class="text-inportant-resalt">
                <em>Todo el trabajo realizado a la iglesia fue con material 100% natural.</em>
            </p>
        </div>
        <div id="gallery" class="container-gallery">
            {% for i in (1..12) %}
            <img alt="{{page.title}}" src="/assets/images/gallerys/san-jeronimo/arcada-principal/thumbnail/{{i}}.jpg"
            data-image="/assets/images/gallerys/san-jeronimo/arcada-principal/{{i}}.jpg" data-description="{{page.title}}">
            {% endfor %}
        </div>
        <h2 class="separador-gallery"><span>Arcada Lateral</span></h2>
        <div id="gallery-1" class="container-gallery">
            {% for i in (1..6) %}
            <img alt="{{page.title}}" src="/assets/images/gallerys/san-jeronimo/arcada-lateral/thumbnail/{{i}}.jpg"
            data-image="/assets/images/gallerys/san-jeronimo/arcada-lateral/{{i}}.jpg" data-description="{{page.title}}">
            {% endfor %}
        </div>
    </div>
</div>