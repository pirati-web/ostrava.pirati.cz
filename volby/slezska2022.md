---
layout: communal-elections
title: Volby 2022 - 4 vize pro hezkou Slezskou 
campaignCategoryUid: slezska2022
candidateListUid: slezska
---

Nabízíme vám naše 4 vize pro hezkou Slezkou. Slezská jako bezpečné a příjemné místo pro život a sport, podpořené chytrými technologiemi.

<section class="o-section o-section--spaceBot">
  <div class="o-section-inner">
    <div class="o-section-block">
      <div class="c-BasicPage">
        <div class="c-BasicPage-content">
          {% assign program = site.program | where: "campaignCategoryUid","slezska2022" | sort: 'order' %}
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
