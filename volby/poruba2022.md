---
layout: communal-elections
title: Volby 2022 - Poruba
campaignCategoryUid: poruba2022
candidateListUid: poruba
---

Piráti připravili pro Porubu v pořadí již čtvrtý volební program. 

Naši základní prioritou bude péče o život ve Porubě. V našem programu se dostávají do popředí mezilidské interakce, zelené plochy nebo čerstvý vzduch, které z pohledu priorit nahrazují beton a cihly.

Obvod příjemný pro život chceme vytvořit na 4 základních pilířích: **Lidé, pirátská politika, udržitelnost a vzdělávání**.

Čtyři roky jsme vás zastupovali na porubské radnici. V politice jsme obstáli a nemáme se za co stydět. Získali jsme cenné zkušenosti, víme, co je reálné a jaké sliby patří do říše snů. Znovu se ucházíme o vaši důvěru, s promyšleným programem postaveným na hodnotách, kterým věříme – na vzájemném respektu, podpoře aktivních i potřebných, úctě k právu, víře v participaci a dialog.

Chceme vám věnovat svůj čas a energii.

<section class="o-section o-section--spaceBot">
  <div class="o-section-inner">
    <div class="o-section-block">
      <div class="c-BasicPage">
        <div class="c-BasicPage-content">
          {% assign program = site.program | where: "campaignCategoryUid","poruba2022" | sort: 'order' %}
          <div class="row small-up-3 medium-up-5 large-up-7">
            {% for item in program %}
              <div class="column column-block">
                <a href="{{ item.url | relative_url }}">
                  <img class="program-icon" src="{{ item.img | prepend: 'assets/img/' | relative_url }}" alt="{{item.shortTitle}}" />
                  <center>
                    <h6>{{item.shortTitle}}</h6>
                  </center>
                </a>
              </div>
            {% endfor %}
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
