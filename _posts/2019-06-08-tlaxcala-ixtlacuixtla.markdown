---
layout: detail_caso_exito
permalink: /tlaxcala-ixtlacuixtla/
image: tlaxcala-ixtlacuixtla.jpg
title: "Tlaxcala Ixtlacuixtla"
description: "Restauración de exterior, torres, fachadas, bóvedas de cañón, cúpulas muros y terrados en el templo o iglesia del poblado de Ixtacuixtla, Tlaxcala..."
---

<div class="container-fluid mt-3 pb-3">
    <div class="container bg-white">
        <div class="p-5 ">
            <h1 class="cnt-title">{{page.title}}</h1>
            <p>
                Para el equipo de DHC ha sido un honor poder reconstruir y rehabilitar todo el exterior, torres, fachadas, bóvedas de cañón, cúpulas muros y reposición  de  dos terrados la iglesia de Ixtacuixtla, Tlaxcala conservando la naturalidad y los detalles arquitectónicos con los que cuenta por el gran valor que representa debido a su antigüedad.
            </p>
            <p class="text-inportant-resalt">
                <em>Todo el trabajo realizado a la iglesia fue con material 100% natural.</em>
            </p>
        </div>
        <div id="gallery" class="container-gallery">
            {% for i in (1..88) %}
            <img alt="{{page.title}}" src="/assets/images/gallerys/tlaxcala-ixtlacuixtla/ixtlacuixtla/thumbnail/{{i}}.jpg"
                data-image="/assets/images/gallerys/tlaxcala-ixtlacuixtla/ixtlacuixtla/{{i}}.jpg" data-description="{{page.title}}">
            {% endfor %}
        </div>
        <h2 class="separador-gallery"><span>Porton</span></h2>
        <div id="gallery-1" class="container-gallery">
            {% for i in (1..8) %}
            <img alt="{{page.title}}" src="/assets/images/gallerys/tlaxcala-ixtlacuixtla/porton/thumbnail/{{i}}.jpg"
            data-image="/assets/images/gallerys/tlaxcala-ixtlacuixtla/porton/{{i}}.jpg" data-description="{{page.title}}">
            {% endfor %}
        </div>
    </div>
</div>