********************************************************************************************************************************
README
********************************************************************************************************************************
ToDo-list Projekti
R0331 - Web sovellusten kehittäminen Javascriptillä 

Tekijät: Huotari Valtteri ja Otto Kainuulainen


********************************************************************************************************************************

Sisällys:

-todolist.html versiot - Vanhemmat versiot sovelluksesta (V1-8)
-todolistFINAL.html - lopullinen versio sovelluksesta
-style.css - sovelluksen käyttämä tyylitiedosto
-styleorgi.css - sovelluksen vanhempi tyylitiedosto
-Mockup.png - konseptikuva sovelluksesta
-raindrops.jpg - sovelluksen taustakuvatiedosto, jota loppujen lopuksi ei käytetty sovelluksessa


********************************************************************************************************************************

SOVELLUS JA SEN KÄYTTÖ:
 Sovellus on yksinkertainen web-sovellus, jolla käytätjä voi luoda oman todo-listan, sekä siirtää valmiit tehtävät erilliseen
 listaan. Tehtäville voi antaa nimen ja eräpäivä.

NEW TASK
 -Sovelluksen UI:n vasemalla puolella on otsikko "New Tasks". Tämän osion kautta tehtäviä voidaan lisätä oikeanpuoleiseen Do-
 listaan.
 -Otsikon alta löytyy pieni tesktikenttä "Task's name" otsikolla, johon tehtävän nimi kirjoitetaan.
  HUOM! Sovellus ei hyväksy tyhjää tekstikenttää. Sovellus ilmoittaa, jos nimi puuttuu.
 -Tekstikentän vieressä on paikka tehtävän eräpäivälle (päivä ja kuukausi), jotka pitää valita valikon valmiista numeroista. 
  HUOM! sovellus ei hyväksy valikon "Day", tai "Month" arvoja. Sovellus ilmoittaa, jos päiväys puuttuu.
 -Näiden alapuolella löytyy "Add" nappi, jota painamalla tehtävän nimi, ja päiväys siirtyvät Do-listaan.
  HUOM! Jos nimieä ei anneta, tai päiväystä ei valita, ei sovellus hyväksy tehtävää, eikä sitä lisätä Do-listaan.
 
DO- JA DONE-LISTAT
 -Sovellusken UI:n oikealla puolella on kaksi listaa: Do-Lista ja Done-Lista
 -Kun uusi tehtävä lisätään "Add" napista, siirtyy se Do-listaan näkyviin.
 -Lisäksi jokaiselle tehtävälle luodaan automaattisesti oma "Check" nappi, jolla kyseinen tehtävä siirretään Do-listalta
  Done-listalle. Näin käyttäjä voi siirtää jo valmiiksi tehdyt tehtävät pois Do-listalta

 

Sovelluksesta puuttuvat ominaisuudet. (Nämä ominaisuudet oli suunniteltu sovellukseen, mutta emme ehtineet lisätä niitä):

- Listojen tallentaminen ja lataaminen myöhempää käyttöä varten
- "Done" -osion tyhjentäminen tehtävistä
- tehtävien kategorisointi värien avulla


********************************************************************************************************************************
