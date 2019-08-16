---
layout: detail_caso_exito
permalink: /catedral-texcoco/
image: catedral-texcoco.jpg
title: "Catedral Texcoco"
description: "Restauración de las seis fachadas que tiene, restaurar los muros de la escuela de la  enseñanza en la catedral de Cuautlalpan, Estado de México..."
---

<div class="container-fluid mt-3 pb-3">
    <div class="container bg-white">
        <div class="p-5 ">
            <h1 class="cnt-title">{{page.title}}</h1>
            <p>
                Para el equipo de DHC ha sido un honor poder reconstruir y rehabilitar las seis fachadas que tiene, restaurar los muros de la escuela de la  enseñanza en la catedral de Cuautlalpan, Estado de México conservando la naturalidad y los detalles arquitectónicos con los que cuenta por el gran valor que representa debido a su antigüedad.
            </p>
            <p class="text-inportant-resalt">
                <em>Todo el trabajo realizado a la iglesia fue con material 100% natural.</em>
            </p>
        </div>
        <div id="gallery" class="container-gallery">
            {% for i in (1..10) %}
            <img alt="{{page.title}}" src="/assets/images/gallerys/catedral-texcoco/catedral/thumbnail/{{i}}.jpg"
                data-image="/assets/images/gallerys/catedral-texcoco/catedral/{{i}}.jpg" data-description="{{page.title}}">
            {% endfor %}
        </div>
        <h2 class="separador-gallery"><span>Escuela-de la Enseñansa</span></h2>
        <div id="gallery-1" class="container-gallery">
            {% for i in (1..13) %}
            <img alt="{{page.title}}" src="/assets/images/gallerys/catedral-texcoco/escuela-de-la-enseniansa/thumbnail/{{i}}.jpg"
                data-image="/assets/images/gallerys/catedral-texcoco/escuela-de-la-enseniansa/{{i}}.jpg" data-description="{{page.title}}">
            {% endfor %}
        </div>
        <h2 class="separador-gallery"><span>Tercera Orden</span></h2>
        <div id="gallery-2" class="container-gallery">
            {% for i in (1..30) %}
            <img alt="{{page.title}}" src="/assets/images/gallerys/catedral-texcoco/tercera-orden/thumbnail/{{i}}.jpg"
                data-image="/assets/images/gallerys/catedral-texcoco/tercera-orden/{{i}}.jpg" data-description="{{page.title}}">
            {% endfor %}
        </div>
    </div>
</div>