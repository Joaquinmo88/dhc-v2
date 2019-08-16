---
layout: detail_caso_exito
permalink: /santiago-tepetitlan/
image: santiago-tepetitlan.jpg
title: "Santiago Tepetitlan"
description: "Restauración de la torre y bóveda de cañón inconclusa de la iglesia de Santiago Tepetitlan, San Martín de las Pirámides, Estado de México..."
---

<div class="container-fluid mt-3 pb-3">
    <div class="container bg-white">
        <div class="p-5 ">
            <h1 class="cnt-title">{{page.title}}</h1>
            <p>
                Para el equipo de DHC ha sido un honor poder reconstruir y rehabilitar la torre y bóveda de cañón inconclusa de la iglesia de Santiago Tepetitlan, Estado de México conservando la naturalidad y los detalles arquitectónicos con los que cuenta por el gran valor que representa debido a su antigüedad.
            </p>
            <p class="text-inportant-resalt">
                <em>Todo el trabajo realizado a la iglesia fue con material 100% natural.</em>
            </p>
        </div>
        <div id="gallery" class="container-gallery">
            {% for i in (1..7) %}
            <img alt="{{page.title}}" src="/assets/images/gallerys/santiago-tepetitlan/thumbnail/{{i}}.jpg"
                data-image="/assets/images/gallerys/santiago-tepetitlan/{{i}}.jpg" data-description="{{page.title}}">
            {% endfor %}
        </div>
    </div>
</div>