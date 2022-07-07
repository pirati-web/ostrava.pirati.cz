---
layout: post
category: CLANKY
title: 'Nadpis článku'			#Zachovat jednoduché úvozovky
date: 2019-01-31T08:00:00.000Z	#Datum a čas, kdy má být článek zveřejněn
author: Jméno Příjmení			#Použije se, pokud není vyplněno "authorId"
authorId: jakub.dedek			#Musí existovat profil v "./_people/"
image: posts/uvodni-obrazek.jpg	#Musí existovat v "./assets/img/posts/, rozlišení 1200x628px"
tags:						#První písmeno velké, s diakritikou, v případě dvou slov (např. jméno a příjmení) spojené pomlčkou. Seznam již použitých tagů je zde: https://mrak.pirati.cz/s/aJM27bpD7QfDCwg
  - Město/obvod			#Ostrava-Jih
  - Programová oblast		#Transparence
  - Osoby			#Lukáš-Černohorský
  - Spojený tag			#Evropská-komise (tag o dvou slovech vždy spojit pomocí "-")
  - Kauza			#Další relevantní tagy
---

Ostrava, 31. ledna 2019 – **Místo a datum vždy v tomto tvaru! Posty musí být každý ve vlastním souboru pojmenovaném datumem a nejakym nazvem, například _posts/2019-01-41-rucnikovy-den.md. Tento název se pak objeví v adrese, tedy xxx.pirati.cz/aktuality/rucnikovy-den.html. Perex vždy tučně.**

Odděluje perex a text čárou:
<hr />

Mezi odstavci musí být vždy jeden prázdný řádek.

>„Přímá řeč se odděluje do vlastního odstavce, který je graficky odělen. Nezapomeňte správný, Český tvar úvozovek, tak jako jsou v této poznámce.”

Vložení obrázku (všechny obrázky by měly mít shodné rozměry, nebo aspoň šířku). Nezapomeň zmínit autora a licenci pod kterou je obrázek zveřejněn - ukázku viz na konci šablony.

{% asset 'articles/cesta_k_obrazku/jmeno-obrazku.jpg' alt='Text který se objeví místo obrázku, pokud ten nelze zobrazit' %}

<p style="text-align: center">
<i>Popis obrázku, vystředěný a italikou.</i>
</p>

Vložení odkazu na lokální soubor:

[Text odkazu]({{'jmeno-soubor.pdf' | prepend: '/assets/pdf/' | relative_url}} "Text který se objeví po najetí na odkaz")

# Nadpis H1

## Nadpis H2

##### Nadpis H5

**Toto je bold text**

__Toto je také bold text__

*Toto je text italikou*

_Toto je také text italikou_

~~Toto je přeškrtnutý text~~

Avšak toto je ~spodní index~  a ^horní index^

1. První položka číslovaného seznamu
2. Druhá položka číslovaného seznamu

Všechny následující příklady seznamu jsou ekvivalentní:

* Seznam

- Opět seznam

+ A zase seznam

Co když děláš seznam a potřebuješ v jedné položce třeba adresu na více řádků? Použij na konci řádku dvě mezery:

- email: jakub.pirat@pirati.cz
- telefon: +420 609 112 777
- adresa:  
Ulice Johna Silvera 1  
Ostrov pokladů  
- datová schránka: pffu666

[Toto je text odkazu](https://www.pirati.cz "Text který se objeví po najetí na odkaz")

Pokud je potřeba nezalomitelná mezera, použij &nbsp;
Třeba OS&nbsp;X.

Pokud chceš použít v textu nějaký znak, který Markdown používá v textu pro formátování, dej před něj znak \.
Třeba \* Toto nebude seznam.

Text který má být kůs kódu se uzavírá mezi obrácené úvozovky, viz příklad:
 toto je `kód`.

Jednoduchá tabulka:

| **První řádek tabulky** | **druhý sloupec** |
|---|---|
| Druhý řádek tabulky | druhý sloupec |
| Třetí řádek tabulku | druhý sloupec |

A pokud to vše nestačí, lze použít i  <font color="red">HTML!</font>

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Nulla accumsan, elit
sit amet varius semper, nulla mauris mollis quam, tempor suscipit diam nulla vel
leo. Fusce nibh. Etiam dictum tincidunt diam. Suspendisse nisl. Ut enim ad minim
veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Sed elit dui, pellentesque a, faucibus vel, interdum nec, diam. Etiam
dui sem, fermentum vitae, sagittis id, malesuada in, quam. Fusce tellus. Donec
ipsum massa, ullamcorper in, auctor et, scelerisque sed, est. Class aptent
taciti sociosqu ad litora torquent per conubia nostra, per inceptos hymenaeos.
Fusce aliquam vestibulum ipsum. Vestibulum erat nulla, ullamcorper nec, rutrum
non, nonummy ac, erat. Ut enim ad minima veniam, quis nostrum exercitationem
ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur?

Nullam lectus justo, vulputate eget mollis sed, tempor sed magna. Etiam commodo
dui eget wisi. Cras elementum. Etiam dictum tincidunt diam. Aliquam erat
volutpat. Duis sapien nunc, commodo et, interdum suscipit, sollicitudin et,
dolor. Aliquam erat volutpat. Etiam ligula pede, sagittis quis, interdum
ultricies, scelerisque eu. Cras elementum. Vestibulum fermentum tortor id mi.
Etiam quis quam. Mauris elementum mauris vitae tortor. Fusce tellus. Integer
rutrum, orci vestibulum ullamcorper ultricies, lacus quam ultricies odio, vitae
placerat pede sem sit amet enim. Ut enim ad minima veniam, quis nostrum
exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi
consequatur?

---

Poznámka o autorovi licenci použitého obrázku v HTML:

Úvodní obrázek zdroj: Lukáš Mižoch [<a href="https://creativecommons.org/licenses/by/3.0">CC BY 3.0</a>], <a href="https://commons.wikimedia.org/wiki/File:ArcelorMittal_Ostrava,_pohled_z_Nov%C3%A9_radnice,_srpen_2011.jpg">z Wikimedia Commons</a>

nebo podobně v Markdown:

Úvodní obrázek zdroj: [Zuzana Klusová]({{'zuzana-klusova' | prepend: '/lide/' | relative_url}}) \[[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.cs)\].

- - -
