---
layout: detail_caso_exito
permalink: /temamantla/
image: temamantla.jpg
title: "Temamatla"
description: "Restauración de copulin, torre, mantenimiento al porton y pintura interior de la iglesia de Temamatla, Estado de México..."
---

<div class="container-fluid mt-3 pb-3">
    <div class="container bg-white">
        <div class="p-5 ">
            <h1 class="cnt-title">{{page.title}}</h1>
            <p>
                Para el equipo de DHC ha sido un honor poder reconstruir y rehabilitar el copulin, torre,mantenimiento al porton y pintura interior de la iglesia de Temamatla, Estado de México conservando la naturalidad y los detalles arquitectónicos con los que cuenta por el gran valor que representa debido a su antigüedad.
            </p>
            <p class="text-inportant-resalt">
                <em>Todo el trabajo realizado a la iglesia fue con material 100% natural.</em>
            </p>
        </div>
        <div id="gallery" class="container-gallery">
            {% for i in (1..22) %}
            <img alt="{{page.title}}" src="/assets/images/gallerys/temamantla/temamantla/thumbnail/{{i}}.jpg"
                data-image="/assets/images/gallerys/temamantla/temamantla/{{i}}.jpg" data-description="{{page.title}}">
            {% endfor %}
        </div>
        <h2 class="separador-gallery"><span>Pintura Interior</span></h2>
        <div id="gallery-1" class="container-gallery">
            {% for i in (1..20) %}
            <img alt="{{page.title}}" src="/assets/images/gallerys/temamantla/pintura-interior/thumbnail/{{i}}.jpg"
            data-image="/assets/images/gallerys/temamantla/pintura-interior/{{i}}.jpg" data-description="{{page.title}}">
            {% endfor %}
        </div>
        <h2 class="separador-gallery"><span>Porton</span></h2>
        <div id="gallery-2" class="container-gallery">
            {% for i in (1..8) %}
            <img alt="{{page.title}}" src="/assets/images/gallerys/temamantla/porton/thumbnail/{{i}}.jpg"
            data-image="/assets/images/gallerys/temamantla/porton/{{i}}.jpg" data-description="{{page.title}}">
            {% endfor %}
        </div>
    </div>
</div>