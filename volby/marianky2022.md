---
layout: communal-elections
title: Volby 2022 - Mariánské Hory a Hulváky
campaignCategoryUid: marianky2022
candidateListUid: marianky
---

Náš volební program pro obvod Mariánské Hory a Hulváky navazuje na pirátský program Ostrava 4.0 pro město a je rozdělen do pěti základních oblastí: vzdělání a volný čas, transparence, otevřená radnice, ekonomika,veřejný prostor a investice, sociální záležitosti a bezpečnost a chytrá řešení pro naše občany, které se prolíná s ostatními oblastmi.

Hlavním cílem je vytvořit z našeho obvodu jedno z nejlepších míst k životu v rámci Ostravy. Chceme, aby mohli mít občané zase plnou důvěru k radnici, měli zde dostatek vyhovujícího prostoru ke svému životu a odpočinku.  



<section class="o-section o-section--spaceBot">
  <div class="o-section-inner">
    <div class="o-section-block">
      <div class="c-BasicPage">
        <div class="c-BasicPage-content">
          {% assign program = site.program | where: "campaignCategoryUid","magistrat2018" | sort: 'order' %}
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
