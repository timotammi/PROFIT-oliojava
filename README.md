PROFIT-oliojava
===============

Linkki kurssin verkkosivuille:

Sisältö

Java1: keskiviikko 14.1.2015 harjoitukset, esimerkit ja tehtävät


#Ohje kurssirepositoryn lisäämiseksi Eclipseen#

##Luo oma haara kurssireposta##

Kirjaudu www.github.com
Hae oikea repo (find: "profit olio"
1. Voit lisätä repon kytättäväksi, eli github ilmoittaa muutoksista jne. (watch)
2. Luo kopio repositorysta itsellesi (fork)
3. Mene omille sivuillesi ja avaa kyseinen repo

##Tuo repo Eclipseen##

1. File -> Import -> Git -> Projects from Git -> Clone URL:
2. Täytä URL-kenttään oman sivusi projektin URL
3. Täytä autentikaatioon Github tunnuksesi ja salasanasi
4. Laita poluksi U:/git/omanimi/PROFIT-oliojava
5. Project Explorerissa pitäisi nyt näkyä "Kurssiprojekti" niminen Java-projekti.

##Herjaaminen JAR-paketista##

1. Graphics.jar tiedoston polku on väärin (koska absoluuttinen linkki)
2. Lisätkäämme se uudestaan: valitse oikea projekti
3. Ylävalikosta Project -> Properties -> Libraries
4. Poista graphics.jar (remove)
5. Lisää uudestaan Add Jar -> Kurssiprojekti -> Jar
