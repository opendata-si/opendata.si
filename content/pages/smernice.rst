:title: Smernice za prispevke v skupnosti Open Data Slovenija
:url: /
:save_as: smernice.html

.. |br| raw:: html

   <br />

Smernice za prispevke v skupnosti Open Data Slovenija
=====================================================

Spodnji zapis predstavlja smernice in dobre prakse do katerih smo prišli skozi naše napake in opazovanje dobrih praks in napak podobnih skupnosti v tujini. Osnovna ideja je, da se splača pogovarjati in komu povedati kaj želiš naredit, preden na programiranju zgubiš teden ali več časa. Če gre za kakšne splošne podatke je velika verjetnost, da jih je kdo že pridobil ali pa je del naloge že naredil.

|br|

Komunikacija
============

- Pred začetkom dela, pošlji na `dopisni seznam </#kontakt-dopisni-seznam>`_ kratko sporočilo na katerih podatkih in virih nameravaš delat. S tem daš možnost ostalim, ki morda delajo na tem ali pa jih bo kasneje zanimalo dobiti te podatke, da te kontaktirajo in uporabijo ali nadaljujejo tvoje delo.
- Ob vsaki večji delujoči različici API-ja ali novem setu pošlji kratko sporočilo na dopisni seznam, da ga bo lahko še kdo drug uporabil. Seveda povej še ostalim (blog, Twitter, Facebook, osebno na srečanjih).

|br|

Podatki
=======

V primeru, da imaš podatke, ki so v obliki enkratne baze, ti priporočamo da jih objaviš na kakšnem Github ali Bitbucket repozitoriju. S tem se boš izognil problemom z gostovanjem čez nekaj let. V primeru, da rabiš pomoč z gostovanjem se nam javi na listo in bomo uredili mirror.

Za podatke je idealno, če:
- So v obliki, ki je berljiva računalnikom (CSV, XLS, SQL, JSON ipd.), seveda z ozirom na uporabljeno tehnologijo in vrsto podatkov.
- Imajo priložen opis sheme in stolpcev/polj.
- Imajo priložen splošen opis podatkov z relevantnimi datumi (čas prenosa, časovni interval na katerega se nanašajo podatki).
- Vsebujejo skripte in navodila kako lahko nekdo sam pripravi te podatke iz vira. Obstaja velika verjetnost, da imajo podatki časovno komponento (npr. mesečno poročilo) in da jih bo kdo želel še kdaj posodobiti.
- Imajo kontakt avtorja.

|br|

API
===

API lahko omogoča lažji dostop npr. mobilnim napravam do fiksnih podatkov ali pa predeluje druge strani (npr. HTML) v REST/JSON obliko s katero je iz mobilne aplikacije lažje delati.

Za API je idealno, če:
- Ima splošni opis ter metod, ki jih podpira,
- podpira JSON(P)
- vrača čas podatkov (torej kdaj so bili prenešeni iz izvora),
- ima kontaktni naslov avtorja in
- ima javno objavljeno kodo in navodila za uporabo.

|br|

ZDIJZ
=====

V Sloveniji imamo zakon `Zakon o dostopu do informacij javnega značaja <https://www.ip-rs.si/informacije-javnega-znacaja/dostop-do-informacij/>`, ki omogoča, da določene informacije iz področja javne uprave zahtevaš v računalniško berljivi obliki. Zgornja povezava je dober vir začetnih informacij. V primeru vprašanj in težav pa se prav tako lahko javiš na naš dopisni seznam in morda ti bo lahko kdo pomagal.

Ko enkrat pridobiš podatke na podlagi ZDIJZ, jih lahko v večini primerov javno objaviš, da ne bo potrebno naslednjemu razvijalcu še enkrat iti skozi postopek uradnega zahtevka.
