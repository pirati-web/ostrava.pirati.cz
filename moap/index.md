---
layout: communal-elections
title: Piráti Moravská Ostrava a Přívoz
campaignCategoryUid: moap2018
candidateListUid: moap
---

> Moravská Ostrava a Přívoz je naším společným domovem a Piráti se budou snažit o to, aby se nám zde spolu žilo co nejlépe, a to díky pro občany transparentnímu fungování a hospodaření radnice, dostupným a kvalitním službám, efektivní dopravě, atraktivnímu veřejnému prostoru a moderní architektuře, lepšímu životnímu prostředí, kvalitní kultuře, sportovnímu vyžití, propojeným sídlištím s centrem města, udržované zeleni a pocitu bezpečnosti.

<section class="o-section o-section--spaceBot">
  <div class="o-section-inner">
    <div class="o-section-block">
      <div class="c-BasicPage">
        <div class="c-BasicPage-content" style="margin: auto; max-width: 900px;">
          {% assign program = site.program | where: "campaignCategoryUid","moap2018" | sort: 'order' %}
          <div class="row small-up-3 medium-up-5 large-up-5">
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

