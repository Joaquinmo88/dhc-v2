---
layout: detail_caso_exito
permalink: /escudo-chiconcuac/
image: escudo-chiconcuac.jpg
title: "Escudo Chiconcuac"
description: "Creacion y diseño del emblematico escudo elaborado en el palacio de Chiconcuac, Estado de México..."
---

<div class="container-fluid mt-3 pb-3">
    <div class="container bg-white">
        <div class="p-5 ">
            <h1 class="cnt-title">{{page.title}}</h1>
            <p>
                Para el equipo de DHC ha sido un honor poder crear y diseñar el emblematico escudo elaborado en el palacio de Chiconcuac, Estado de México con materiales naturales y detalles arquitectónicos y esculturales con los que cuenta nuestro equipo de trabajo.
            </p>
            <p class="text-inportant-resalt">
                <em>Todo el trabajo realizado en el escudo fue con material 100% natural.</em>
            </p>
        </div>
        <div id="gallery" class="container-gallery">
            {% for i in (1..12) %}
            <img alt="{{page.title}}" src="/assets/images/gallerys/escudo-chiconcuac/thumbnail/{{i}}.jpg"
                data-image="/assets/images/gallerys/escudo-chiconcuac/{{i}}.jpg" data-description="{{page.title}}">
            {% endfor %}
        </div>
    </div>
</div>
