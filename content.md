---
marp: true
theme: gaia
markdown.marp.enableHtml: true
paginate: true
---

<style>

section {
  background-color: #fefefe;
  color: #333;
}

ul {
  list-style: none
}

img[alt~="center"] {
  display: block;
  margin: 0 auto;
}
img[alt~="floatright"] {
  float: right;
}

#video {
   text-align: center;
}

blockquote {
  background: #ffedcc;
  border-left: 10px solid #d1bf9d;
  margin: 1.5em 10px;
  padding: 0.5em 10px;
}
blockquote:before{
  content: unset;
}
blockquote:after{
  content: unset;
}
</style>

<!-- _class: lead -->

# Le (logiciel) libre a-t-il 
# de beaux jours devant lui ?

---

## ~# whoami

Denis GERMAIN

🌅 Site Reliability Engineer

🌃 Auteur sur [blog.zwindler.fr](https://blog.zwindler.fr)*

![width:50](binaries/twitter.png) @zwindler / @zwindler_rflx

**#geek** 🎮 **#SF** 🤖 **#courseAPied** 🏃‍♂️

![bg fit right:40%](binaries/denis.png)

<br/>

**Les slides de ce talk sont sur le blog*

---

<!-- _class: lead -->

# Le (logiciel) libre a-t-il 
# de beaux jours devant lui ?

---

<!-- _class: lead -->

# Dis papa, c'est quoi le (logiciel) libre ?

![bg right:40% fit](binaries/logiciel_libre.png)

---

## Logiciel Libre

Définition GNU (![width:100 margin-right](binaries/fsf_logo.png))

* « Logiciel libre » désigne des logiciels qui respectent la liberté des utilisateurs.

* [...] Les utilisateurs ont la liberté d'exécuter, copier, distribuer, étudier, modifier et améliorer ces logiciels.

> « Free as in free speech, not free beer »

![bg right:25% fit](binaries/richard_stallman.jpg)

---

## Open Source (≠ Logiciel Libre)

Dfinition GNU (encore)

* En 1998, une partie de la communauté a […] commencé à faire […] de l'« open source »

* Le mouvement open source vise à promouvoir le logiciel libre en lui retirant l’aspect idéologique (= politique)

* [GNU.org - Open Source misses the point](https://www.gnu.org/philosophy/open-source-misses-the-point.html)

![bg right:30% fit](binaries/underpants-gnomes-business-plan.png)

---

# Le libre, c'est pas que du logiciel !

Le libre, c'est une philosophie, quasiment un mouvement politique.

Partager des connaissances, de la culture, ça peut s'apparenter à "du libre"

![height:165](./binaries/wikipedia.png) ![height:165](./binaries/creative_commons.png) ![height:165](binaries/openfoodfacts.png) ![height:165](binaries/osmlogo.png)

---


## Free software versus Open source software

Dans la pratique,

* Cette distinction est très peu connue du « grand public IT »
* De nombreux logiciels dits « open source » sont « libres »

![width:600 center](./binaries/thatsexactly.png)

---

<!-- _class: lead -->

# "Libre bashing"

![bg right:50% fit](binaries/Spade-Guy.jpg)

*crédits : AFP*

---

## Voici comment on est vu de l’extérieur

Guillaume Meurice (France Inter) est au Paris Open Source Summit <br/><br/>

<div id=video><video controls="controls" width="800" src="binaries/meurice.mp4"></video></div>

---

## Ennemis (historique) de l’Open Source ?

![center width:400](binaries/ms_logo.jpg)

<div id=video><video controls="controls" width="800" src="binaries/microsoft_dance.mp4"></video></div>

---

## Ennemis de l’Open Source ?

> **Linux est un cancer** qui, au sens de la propriété intellectuelle, corrompt ce qu’il touche

Steve Ballmer (PDG) en 2001 
(*crédits : Dan DeLong*)

![bg right:35% fit](binaries/ballmer_geekwire.jpg)

---

## Ennemis de l’Open Source ?

> Il existe des **communistes d’un genre nouveau**, qui souhaitent abolir toute forme de rémunération pour les musiciens, artistes du cinéma et développeurs de logiciels

Bill Gates en 2005

![bg right:35% fit](binaries/communism.jpg)

---

## Ok pour hier. Mais aujourd'hui ?

Dans le top10 des éditeurs de logiciels dans le monde, 4 sont (très) connues pour leur catalogue de "logiciels propriétaires"

![width:800 center](binaries/top10.png)

---

## ![height:80](binaries/sap_logo.png)

![width:1100 center](binaries/open_source_bashing.jpg)

[zwindler.fr - l’open source bashing a encore de beaux jours devant lui](https://blog.zwindler.fr/2018/10/19/lopen-source-bashing-a-encore-de-beaux-jours-devant-lui/)

---

## ![height:80](binaries/sap_logo.png) "On collecte, on connecte, ça marche"

![width:750 center](binaries/sapbobi4.png)

---

## ![height:65](binaries/oracle.gif)

MySQL est la base de données open source la plus populaire au monde grâce à sa fiabilité, sa facilité d'utilisation et ses performances avérées. (*source : oracle.com*)

![height:38](binaries/also.png) ![height:40](binaries/oracle.gif)

Si vous utilisez MySQL, vous allez devoir sacrifier énormément de stabilité, sécurité et performance. C’est un très vieux système.
**Larry Ellison (PDG d’Oracle) en 2018**

[Tech republic - Why does Oracle keep trashing its own product](https://www.techrepublic.com/article/why-does-oracle-keep-trashing-mysql-its-own-product/)

---

<!-- _class: lead -->

# La communauté Open Source

---

## La communauté Open Source

Les gestionnaires de dépendances / paquets / modules

![height:40](binaries/npm_logo.png) **install**

<div id=video><video controls="controls" width="600" src="binaries/npminstall.mp4"></video></div>

[https://twitter.com/garrows/status/1065217184643768320](https://twitter.com/garrows/status/1065217184643768320)

---

## La communauté Open Source

* Mainteneur unique de **event-stream**

* Package NPM très populaire avec plusieurs millions (!!!) de téléchargements hebdomadaires

* Plus maintenu depuis des années

* Utilisé par de très nombreux packages 
  * *(Et donc de très nombreux logiciels)*

![bg left:27% fit](binaries/tarr2.png)

---

## Et là, c’est le drame

![width:600](binaries/idontknow3.png)

![width:1000](binaries/dominic.png)

[https://github.com/dominictarr/event-stream/issues/116](https://github.com/dominictarr/event-stream/issues/116)

---

## Les "dangers" de l'Open Source

![width:900](binaries/millions2.png)

![width:900](binaries/millions.png)

![bg right:27% fit](binaries/what.jpg)

---

## Heartbleed / Curl

Le problème ne date pas d'hier et ne se limite pas à NPM ! 

Deux autres exemples :

* Curl - virtuellement maintenu par une personne de 1998
* OpenSSL - [faille Heartbleed](https://en.wikipedia.org/wiki/Heartbleed) en 2014

[OneZero - The Internet Relies on People Working for Free](https://onezero.medium.com/the-internet-relies-on-people-working-for-free-a79104a68bcc)

![bg right:35% fit](binaries/dependency.png)

---

<!-- _class: lead -->

# Qui pour sauver l'open source ?

---

## Open source versus Proprietary

<div id="video">
<br/>FIRST<br/>
<b>THEY IGNORE YOU.</b><br/>
THEN</br>
<b>THEY LAUGH AT YOU.</b><br/>
THEN<br/>
<b>THEY FIGHT YOU.</b><br/>
THEN<br/>
<b>YOU WIN.</b><br/>
</div>

---

## Redhat; **the** OSS company

Créée en 1993, entreprise surtout connue pour Redhat Entreprise Linux, CentOS, Fedora, Openshift, ...

* Souvent citée en exemple de l’open source "qui marche"
* 3.4 Md$ de chiffre d'affaire en 2019

![bg right:30% fit](binaries/redhat.jpg)

---

## Et là, c'est le drame (oui, encore...)

![center width:600](binaries/then_they_buy_you2.png)

---

## IBM + redhat = ❤️

![width:600](binaries/IBM_logo.png)

![bg right:40% fit](binaries/selltobuyibm.jpg)

---

<!-- _class: lead -->

# Qui contribue le plus ?

---

## Vous pouvez répéter la question ?

![width:400 center](binaries/question.jpeg)


> Dans le monde, quelle entitée contribue le plus de "code ouvert" ?

---

## Qui contribue le plus ?

Est ce que c'est Redhat ? C'est leur coeur de métier après tout

* ![width:300 center](binaries/nope.jpg)

![bg right:30% fit](binaries/redhat.jpg)

---

## Qui contribue le plus ?

> "Indice sur vos écrans"

**C'est un cloud provider connu**

* ... mais ce n'est certainement pas eux !
* ![width:600 center](binaries/sad_amazon_logo.webp)

---

## Qui contribue le plus ?

Même s'ils sont bons 2èmes, ce n'est pas eux non plus

* ![](binaries/dontbeevil.png)
* ![center width:500](binaries/logo-google.gif)

---

## Les ~~ennemis~~ amis de l'Open Source

![center](binaries/ms_loves_opensource.png)

> « We are all in on open source » 

Satya Nadella (CEO actuel de Microsoft)

[Etude "State of the octoverse" 2018](https://octoverse.github.com)

---

## Encore plus amis de l'Open Source

* 2017 - Microsoft rejoint l'OSI ![height:60](binaries/osi_logo.png)

* 2018 - Microsoft libère 60k brevets

* 2018 - Microsoft achète ![height:60](binaries/github_logo.png)

* 2019 - La ![height:40](binaries/fsf_logo.png) donne une conf' à Redmond

![bg right:30% fit](binaries/Stallman_microsoft.jpg)

[Microsoft saute le pas et met 60 000 brevets à disposition de Linux](https://siecledigital.fr/2018/10/12/microsoft-saute-le-pas-et-met-60-000-brevets-a-disposition-de-linux/)

---

## Toujours plus amis de l'Open Source

* 2020 - Conférence Linux aurait du (COVID-19) avoir lieu au siège, à Redmond !

* 2020 - Microsoft achète ![height:50](binaries/npm_logo.png)

[Site de la WSL Conf 1](https://www.wslconf.dev/wslconf1)

![bg right:30% fit](binaries/satia.png)

---

## Réel changement, openwashing, ou pire ?

Adoption massive des produits open source dans "le cloud" ⇒ Microsoft a intéret à suivre le mouvement

Beaucoup n'ont pas oublié le **"Embrace, Extend and Extinguish"** de Microsoft dans les années "Netscape vs Internet Explorer".

[Embrace, Extend, Extinguish](https://fr.wikipedia.org/wiki/Embrace,_extend_and_extinguish)

---

<!-- _class: lead -->

## TODO Le libre pour sauver le monde

---

## Le libre peut redonner du sens à nos vies

Titre d'un article de Framasoft qui parle de Bernard Stiegler.



[« Le logiciel libre peut redonner sens à nos vies » Bernard Stiegler](https://framablog.org/2012/03/02/bernard-stiegler-logiciel-libre/)

https://mamot.fr/@tnoisette/104647061959753272
https://mamot.fr/@tnoisette/104647071206510013

---

## TODO Calimac

--- 

## Un immeuble de 212 étages dans Flight Simulator

![width:800 center](binaries/flightsim.jpeg)

---

<!-- _class: lead -->

# Conclusion

![bg right:50% fit](binaries/wrap.png)

---

## Conclusion [Sarcarsm ON]

* Logiciel libre != Logiciel Open Source
  * *et tout le monde s’en fout™ ![floatright width:400](binaries/tlmsf.jpg)

* Le libre, ce n’est pas que des logiciels

* L’Open Source c’est le cancer
  * *sauf si on peut faire de l’argent avec

* Faire de l’Open Source fait de vous un ZADiste néocommuniste....
  * ... mais arrêter de maintenir vos projets Open Source met la vie de millions d’innocents en danger

---

## Conclusion [Sarcasm OFF]

Contribuer au libre c'est cool, c'est participer à un monde meilleur


![width:850 center](binaries/nick_craver_ben_lesh.png)

[https://twitter.com/BenLesh/status/1119770730185363456?s=19](https://twitter.com/BenLesh/status/1119770730185363456?s=19)

---

## That's all folks

![width:800 center](binaries/thatsall.jpg)

---

<!-- _class: lead -->

# Des questions ?
# Ca vous a plu ?

![bg left:35% fit](binaries/rage-face-etonnant.jpg)

---

<!-- _class: lead -->

# Bonus !

---

## Bonus Microsoft

La FSF n'est plus ennemi juré de Microsoft, mais ça ne l'empêche pas de troller.

[La FSF envoie à Microsoft un disque dur vide pour récupérer le code source de Windows 7](https://windows.developpez.com/actu/293901/La-FSF-envoie-a-Microsoft-un-disque-dur-vide-pour-recuperer-le-code-source-de-Windows-7-et-demande-a-l-entreprise-de-tenir-aux-engagements-qu-elle-a-pris-envers-la-communaute-du-logiciel-libre/)

[Microsoft and Open Source: An unofficial timeline](https://boxofcables.dev/microsoft-and-open-source-an-unofficial-timeline)

[Brad Smith (président de Microsoft), reconnait que Microsoft a été "on the wrong side of history"](https://www.theregister.com/2020/05/15/microsoft_brad_smith_open_source/)

---

## Bonus communauté

[Victor Stinner a propos des termes offençants et des réactions de la communauté](https://twitter.com/VictorStinner/status/1295237763697180672?s=20). Il a reçu des commentaires comme "I would want him dead" suite à un talk à la PyCon où il parle simplement de retirer des termes offençants dans Python.

[Rubocop, un framework en Ruby, a vu une partie de sa communauté exiger du mainteneur principal](https://twitter.com/bitfield/status/1269975970200641537?s=19) qu'il change de nom suite au mouvement #BlackLivesMatter

---

## Bonus licence

Zimbra devient open core
https://twitter.com/abrianceau/status/1293837833979994114?s=20

Sentry
https://blog.sentry.io/2019/11/06/relicensing-sentry
https://github.com/todogroup/survey/tree/master/2019

---

## Bonus coup de gueule

[Sebsauvage à propos de WSL](https://framapiaf.org/@sebsauvage/104756899715214271)

[Sebsauvage encore, à propos de Brad Smith qui demande l'équivalent d'un serment d'Hypocrate aux informaticiens](https://framapiaf.org/@sebsauvage/104663776259527309)

---

## Et l'état dans tout ça ?

* [Open source et ministère de la défense](https://twitter.com/etiennegonnu/status/1218202788699820037?s=19)
* [NextInpact - Le logiciel libre arrive au sein de la Centrale d'achat de l'informatique hospitalière](https://www.nextinpact.com/article/43372/le-logiciel-libre-arrive-au-sein-centrale-dachat-informatique-hospitaliere)

---

AstronoGeek, Youtube vs Peertube
https://twitter.com/Skeptikon1/status/1192106002457473030

Leo Grasset / Dirty Biology
https://twitter.com/search?q=from%3A%40zwindler%20to%3A%40dirtybiology&src=typed_query

Bouletcorp versus David Revoy