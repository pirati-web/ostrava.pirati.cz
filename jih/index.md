---
layout: communal-elections
title: Piráti Ostrava-Jih
campaignCategoryUid: jih2018
candidateListUid: jih
---

> Náš městský obvod je velice rozmanitý nejen historicky a geograficky, ale hlavně lidsky. Žijeme zde všichni spolu, avšak každý s jinými potřebami a přáními. Piráti z Jihu chtějí naslouchat a spolu s dalšími občany pomáhat Jihu v jeho rozvoji. Největší městský obvod si tu péči zaslouží.

<section class="o-section o-section--spaceBot">
  <div class="o-section-inner">
    <div class="o-section-block">
      <div class="c-BasicPage">
        <div class="c-BasicPage-content" style="margin: auto; max-width: 900px;">
          {% assign program = site.program | where: "campaignCategoryUid","jih2018" | sort: 'order' %}
          <div class="row small-up-4 medium-up-5 large-up-5">
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

