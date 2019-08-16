---
layout: detail_caso_exito
permalink: /cuauhtlalpan/
image: cuauhtlalpan.jpg
title: "Cuautlalpan"
description: "Restauración de la achada, torre, muros nivelación de suelo elaboración de filtros y colocación de rejillas para canalizar la humedad de la iglesia de Cuautlalpan, Estado de México..."
---

<div class="container-fluid mt-3 pb-3">
    <div class="container bg-white">
        <div class="p-5 ">
            <h1 class="cnt-title">{{page.title}}</h1>
            <p>
                Para el equipo de DHC ha sido un honor poder reconstruir y rehabilitar la fachada, torre,muros nivelación de suelo elaboración de filtros y colocación de rejillas para canalizar la humedad de la iglesia de Cuautlalpan, Estado de México conservando la naturalidad y los detalles arquitectónicos con los que cuenta por el gran valor que representa debido a su antigüedad.
            </p>
            <p class="text-inportant-resalt">
                <em>Todo el trabajo realizado a la iglesia fue con material 100% natural.</em>
            </p>
        </div>
        <div id="gallery" class="container-gallery">
            {% for i in (1..35) %}
            <img alt="{{page.title}}" src="/assets/images/gallerys/cuauhtlalpan/fachada/thumbnail/{{i}}.jpg"
            data-image="/assets/images/gallerys/cuauhtlalpan/fachada/{{i}}.jpg" data-description="{{page.title}}">
            {% endfor %}
        </div>
        <h2 class="separador-gallery"><span>Interior</span></h2>
        <div id="gallery-1" class="container-gallery">
            {% for i in (1..25) %}
            <img alt="{{page.title}}" src="/assets/images/gallerys/cuauhtlalpan/interior/thumbnail/{{i}}.jpg"
            data-image="/assets/images/gallerys/cuauhtlalpan/interior/{{i}}.jpg" data-description="{{page.title}}">
            {% endfor %}
        </div>
        <h2 class="separador-gallery"><span>Torre</span></h2>
        <div id="gallery-2" class="container-gallery">
            {% for i in (1..27) %}
            <img alt="{{page.title}}" src="/assets/images/gallerys/cuauhtlalpan/torre/thumbnail/{{i}}.jpg"
            data-image="/assets/images/gallerys/cuauhtlalpan/torre/{{i}}.jpg" data-description="{{page.title}}">
            {% endfor %}
        </div>
    </div>
</div>