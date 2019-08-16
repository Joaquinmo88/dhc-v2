---
layout: detail_caso_exito
permalink: /nexquipayac/
image: nexquipayac.jpg
title: "Nexquipayac"
description: "Restauración de la arcada real de la iglesia de San Cristóbal Nexquipayac, Estado de México..."
---

<div class="container-fluid mt-3 pb-3">
    <div class="container bg-white">
        <div class="p-5 ">
            <h1 class="cnt-title">{{page.title}}</h1>
            <p>
                Para el equipo de DHC ha sido un honor poder reconstruir y rehabilitar la arcada real de la iglesia de San Cristóbal Nexquipayac, Estado de México conservando la naturalidad y los detalles arquitectónicos con los que cuenta por el gran valor que representa debido a su antigüedad.
            </p>
            <p class="text-inportant-resalt">
                <em>Todo el trabajo realizado a la iglesia fue con material 100% natural.</em>
            </p>
        </div>
        <div id="gallery" class="container-gallery">
            {% for i in (1..18) %}
            <img alt="{{page.title}}" src="/assets/images/gallerys/nexquipayac/thumbnail/{{i}}.jpg"
                data-image="/assets/images/gallerys/nexquipayac/{{i}}.jpg" data-description="{{page.title}}">
            {% endfor %}
        </div>
    </div>
</div>