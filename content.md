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

🌅 SRE chez ![height:30](binaries/deezer_logo.png)

🌃 Auteur sur [blog.zwindler.fr](https://blog.zwindler.fr)*

![width:50](binaries/twitter.png) @zwindler / @zwindler_rflx

**#geek** 🎮 **#SF** 🤖 **#courseAPied** 🏃‍♂️

![bg fit right:40%](binaries/denis.png)

<br/>

**Les slides de ce talk sont sur le blog*

---

## ![height:50](binaries/deezer_logo.png)

TODO

---

## Que fait un SRE chez ![height:40](binaries/deezer_logo.png) ?

TODO

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

Logiciel libre (définition GNU) ![width:100 margin-right](binaries/fsf_logo.png)

* « Logiciel libre » désigne des logiciels qui respectent la liberté des utilisateurs.

* [...] Les utilisateurs ont la liberté d'exécuter, copier, distribuer, étudier, modifier et améliorer ces logiciels.

> « Free as in free speech, not free beer »

---

# Culture libre

Le libre ne se limite pas au développement logiciel

![width:250](./binaries/wikipedia.png) ![width:500](./binaries/creative_commons.png)

---

## Open Source (≠ Logiciel Libre)

Open source (définition GNU toujours)

* En 1998, une partie de la communauté a […] commencé à faire […] de l'« open source »

* Le mouvement open source vise à promouvoir le logiciel libre en lui retirant l’aspect idéologique (= politique)

![bg right:30% fit](binaries/underpants-gnomes-business-plan.png)

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

Crédits : AFP

---

## Voici comment on est vu de l’extérieur

Guillaume Meurice (France Inter) est au Paris Open Source Summit

<div id=video><video controls="controls" width="800" src="binaries/meurice.mp4"></video></div>

---

## Ennemi (historique) de l’Open Source ?

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

## Libre bashing en entreprise

Dans le top10 des éditeurs de logiciels dans le monde, 4 sont (très) connues pour leur catalogue de "logiciels propriétaires"

TODO

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

---

## La communauté Open Source

Les gestionnaires de dépendances / paquets / modules

![height:40](binaries/npm_logo.png) **install**

TODO npminstall.mp4

[https://twitter.com/garrows/status/1065217184643768320](https://twitter.com/garrows/status/1065217184643768320)

---

## La communauté Open Source

* Développeur, mainteneur unique de event-stream

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

## TODO

Rubocop
https://twitter.com/bitfield/status/1269975970200641537?s=19


---

<!-- _class: lead -->

# Qui pour sauver l'open source ?

---

## Open source versus Proprietary

FIRST
**THEY IGNORE YOU.**
THEN
**THEY LAUGH AT YOU.**
THEN
**THEY FIGHT YOU.**
THEN
**YOU WIN.**

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

## Qui contribue le plus ?

Redhat ? C'est leur coeur de métier après tout
* NOPE !

TODO

![bg right:30% fit](binaries/redhat.jpg)

---

## Qui contribue le plus ?

> "Indice sur vos écrans"

**C'est un cloud provider connu**

* ... mais ce n'est certainement pas eux !
* Amazon

TODO

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

* 2017 - Microsoft rejoint l'Open Source Initiative ![height:80](binaries/osi_logo.png)

* 2018 - Microsoft libère 60k brevets et achète ![height:80 ](binaries/github_logo.png)

* 2019 - La FSF ![height:80](binaries/fsf_logo.png) donne une conférence à Redmond !

[Microsoft saute le pas et met 60 000 brevets à disposition de Linux](https://siecledigital.fr/2018/10/12/microsoft-saute-le-pas-et-met-60-000-brevets-a-disposition-de-linux/)

---

## Toujours plus amis de l'Open Source

![center](binaries/satia.png)

* 2019 - Ajout du noyau Linux dans Windows 10

* 2020 - Conférence Linux aurait du avoir lieu au siège , à Redmond !

[https://www.wslconf.dev/wslconf1]()

---

<!-- _class: lead -->

## TODO La guerre du cloud

https://blog.sentry.io/2019/11/06/relicensing-sentry
https://twitter.com/Skeptikon1/status/1192106002457473030
https://github.com/todogroup/survey/tree/master/2019

---

<!-- _class: lead -->

## TODO culture libre

--- 

<!-- _class: lead -->

## TODO Le libre pour sauver le monde

https://framapiaf.org/@sebsauvage/104663776259527309
https://mamot.fr/@tnoisette/104647061959753272
https://mamot.fr/@tnoisette/104647071206510013



---

## Et ![height:50](binaries/deezer_logo.png) dans tout ça ?

Nous aussi, on s’ouvre à l’Open Source

* De nombreux développeurs contribuent (et les OPS aussi !)

* Plusieurs projets open-sourcés sur Github [github.com/deezer](https://github.com/deezer)
  * En particulier ![height:40](binaries/spleeter_logo.png)

Et plus à suivre !

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

Une situation résumée en deux tweets

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


ICE Palantir

---

## Déclaration versus actes

---

## Et l'état dans tout ça ?


https://twitter.com/etiennegonnu/status/1218202788699820037?s=19

---

https://windows.developpez.com/actu/293901/La-FSF-envoie-a-Microsoft-un-disque-dur-vide-pour-recuperer-le-code-source-de-Windows-7-et-demande-a-l-entreprise-de-tenir-aux-engagements-qu-elle-a-pris-envers-la-communaute-du-logiciel-libre/

https://boxofcables.dev/microsoft-and-open-source-an-unofficial-timeline/amp/?__twitter_impression=true

---

https://twitter.com/lea_linux/status/1217523083319431170?s=19


https://twitter.com/Arawa_fr/status/1262129262951305216?s=19


Zimbra open core
https://twitter.com/abrianceau/status/1293837833979994114?s=20


https://www.linkedin.com/posts/moula-badji-8550b773_vague-de-licenciements-chez-vmware-channelnews-activity-6700516507459428352-J0Lt

https://twitter.com/VictorStinner/status/1295237763697180672?s=20

https://botsin.space/@xkcdbot/104706923054981209

https://twitter.com/nextinpact/status/1296067530763595776?s=20

https://twitter.com/liamosaur/status/1296305262144364544?s=20

https://framapiaf.org/@sebsauvage/104756899715214271




