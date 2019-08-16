---
layout: detail_caso_exito
permalink: /tequisistlan/
image: tequisistlan.jpg
title: "Tequisistlán"
description: "Restauración de muros exteriores en el claustro la iglesia de Tequisistlán, Tezoyuca, Estado de México..."
---

<div class="container-fluid mt-3 pb-3">
    <div class="container bg-white">
        <div class="p-5 ">
            <h1 class="cnt-title">{{page.title}}</h1>
           <p>
                Para el equipo de DHC ha sido un honor poder reconstruir y rehabilitar los muros, consolidación de fracturas y suministro de mampostería en la iglesia de Tequisistlán, Tezoyuca, Estado de México conservando la naturalidad y los detalles arquitectónicos con los que cuenta por el gran valor que representa debido a su antigüedad.
            </p>
            <p class="text-inportant-resalt">
                <em>Todo el trabajo realizado a la iglesia fue con material 100% natural.</em>
            </p>
        </div>
        <div id="gallery" class="container-gallery">
            {% for i in (1..55) %}
            <img alt="{{page.title}}" src="/assets/images/gallerys/tequisistlan/thumbnail/{{i}}.jpg"
                data-image="/assets/images/gallerys/tequisistlan/{{i}}.jpg" data-description="{{page.title}}">
            {% endfor %}
        </div>
    </div>
</div>