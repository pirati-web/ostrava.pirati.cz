---
layout: communal-elections
title: Komunální program Ostrava 4.0
campaignCategoryUid: magistrat2022
candidateListUid: magistrat
---

<section class="o-section o-section--spaceBot">
  <div class="o-section-inner">
    <div class="o-section-block">
      <div class="c-BasicPage">
        <div class="c-BasicPage-content">
          {% assign program = site.program | where: "campaignCategoryUid","magistrat2022" | sort: 'order' %}
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

Piráti připravili pro Ostravu v pořadí již čtvrtý volební program. Jedná se o nejpropracovanější pirátský program pro Ostravu v historii. Pracovali na něm specialisté z různých odvětví. Naším cílem je vytvořit z Ostravy moderní evropskou metropoli. 

Podle nás Ostrava nemá konkurovat Brnu nebo Plzni. Má konkurovat Lyonu, Manchesteru, nebo Milánu. Chceme město řídit projektově a strategicky na základě jasného plánu, dokumentů a priorit.  

V roce 2023 přijme nové vedení města nový strategický plán. Chceme, aby fajnova 2.0 začínala u člověka v daleko větší míře, než tomu bylo dosud. Ostrava zatím v plánování kladla na první místo budovy, potom prostor a až nakonec trochu života. V minulém volebním období se hodně mluvilo o nové koncertní síni, o nových jatkách, o novém mrakodrapu. 

Naším cílem je tento přístup změnit. Naši základní prioritou bude péče o život ve městě. V našem programu se dostávají do popředí mezilidské interakce, zelené plochy nebo čerstvý vzduch, které z pohledu priorit nahrazují beton a cihly.

Našim hlavním cílem je vrátit do Ostravy radost. Radost ze života. Slavný dánský architekt Jan Gehl říká, že dobré město poznáte podle toho, že funguje jako dobrá párty. Lidé zapomenou na čas a chtějí tady zůstat a bavit se. Přesně taková má být podle nás Ostrava.

**Princip 7 a 70 a čtyři základní pilíře nové Ostravy**

Pokud má být Ostrava příjemným místem pro život musíme při plánování myslet na všechny. Nejen na mladé nebo na staré. Nejen na řidiče, ale i na cyklisty. Nejen na chodce, ale i na vozíčkáře a maminky s kočárky. Pokud dokážeme vytvořit přátelské město pro děti ve věku 7 let i pro seniory ve věku 70 let, je slušná šance, že se v Ostravě bude líbit i všem ostatním.

Město příjemné pro život chceme vytvotvořit na 4 základních pilířích: Lidé a komunity, Lokální ekonomika, Město pro život a Smart řešení jako nadstavba, která se prolíná všemi oblastmi.
