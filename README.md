piratenpartij.nl
================

Codebase voor het Piratenpartij-thema in de Newsletter plugin van
WordPress.

Licentie
--------

Dit is vrije software onder de CC0 1.0 Universal Public Domain
Dedication of, naar je eigen inzicht, enige latere versie.

Bijdragen
---------

Je kunt op twee manieren bijdragen: door een patchfile te mailen, of
middels Git. Git heeft in verband met de snellere workflow onze
voorkeur.

Bijdragen
---------

Je kunt op twee manieren bijdragen: door een patchfile te mailen, of
middels Git. Git heeft in verband met de snellere workflow onze
voorkeur.

**Via patches**
Maak je wijzigingen, en maak een patchfile met `diff` en `patch`. Deze
kun je mailen naar <ict@piratenpartij.nl>

**Via Git(Hub)**
Ben je nog niet bekend met Git, en heb je 15 minuten? Kijk dan eens op
<http://try.github.io> voor een snelcursus van de basis. Je kan ook
altijd het ICT-team om hulp vragen, zie onder voor contactinformatie.

(Noot: onderstaande gaat uit van command line Git - er zijn als je de
voorkeur hiervoor hebt, ook diverse GUI-clients beschikbaar voor elk
besturingssysteem.)

1. Maak een account aan bij GitHub als je die nog niet
   hebt.
2. Fork deze repository naar je eigen account.
3. Clone je fork:
   `git clone https://github.com/%jeUsername%/WP.Newsletter.Piratenpartij.git`.
4. Optioneel (maar aangeraden), maak een nieuwe branch om in te
   werken: `git checkout %naamVanJeBranch%`.
4. Maak je wijzigingen in je favoriete editor.
5. Voeg de gewijzigde bestanden toe aan je volgende commit:
   `git add relatief/pad/naar/bestand`
6. Commit je wijzigingen: `git commit -m "%korte samenvatting%"`
7. Push je wijzigingen naar je fork: `git push`
8. Tevreden? Stuur een pull request naar deze repository!

Hulp nodig? Zie hieronder voor contactgegevens.

Branches
--------

Deze repository heeft twee belangrijke branches: `master` en `deploy`.
`master` is onze ontwikkelbranch, pull requests en commits gaan altijd
naar deze branch. `deploy` is de huidige live-omgeving.

De deploy branch is gekoppeld aan Jenkins, een continuous integration-
systeem. Deze test de wijzigingen in deze branches (en voor pull
requests), en voert automatisch de wijzigingen door op de server als
er geen grote problemen gevonden zijn.

**master**: De hoofd-ontwikkelbranch. Commits moeten uiteindelijk hier
uitkomen. De testomgeving is te vinden op

**deploy**: De live-omgeving. Hier mag niet rechtstreeks een commit
naar gestuurd worden; wel kun je mergen vanuit master (eventueel kun
je specifieke commits mergen).

De enige uitzondering hierop, is dat de server zelf af en toe `deploy`
kan committen.

Deze wijzigingen moet je logischerwijs weer terug mergen naar
`master`.

Contact
-------

* Mail: <ict@piratenpartij.nl>
* IRC:  <ircs://nl.pirateirc.net:994/#ppnl-ict>

Ook kun je kijken op het ICT-subforum op
<https://forum.piratenpartij.nl>.
