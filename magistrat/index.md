---
layout: borough
title: Piráti na ostravském magistrátě
shortTitle: Magistrát
boroughBannerDefault: banner-default-blank.jpg
boroughBannerMobile: banner-mobile.jpg
boroughTag: Ostrava
boroughTeamUid: magistrat
linkCategories:
  - name: Sociální sítě
    links:
    - name: Facebook
      link: https://www.facebook.com/piratiostrava/
  - name: Komunální volby 2018
    links:
    - name: Kompletní program
      link: program/magistrat2018/otevrena-transparentni-participace/
    - name: Kandidátka a výsledky
      link: https://volby.cz/pls/kv2018/kv1111?xjazyk=CZ&xid=1&xdz=3&xnumnuts=8106&xobec=554821&xstat=0&xvyber=0
    - name: Povolební strategie
      link: assets/pdf/povolebni-strategie.pdf
  - name: Komunální volby 2022
    links:
    - name: Kompletní program
      link: program/magistrat2022/programovy-bod-1/
---

> Ostrava je naším společným domovem a Piráti se budou snažit o to, aby se nám zde spolu žilo co nejlépe, a to díky pro občany transparentnímu fungování a hospodaření magistrátu, dostupným a kvalitním službám, efektivní dopravě, atraktivnímu veřejnému prostoru a moderní architektuře, lepšímu životnímu prostředí, kvalitní kultuře, sportovnímu vyžití, udržované zeleni a pocitu bezpečnosti.

<!--<section class="o-section o-section--spaceBot">
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
</section>-->
