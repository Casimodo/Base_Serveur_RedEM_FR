[forks-shield]: https://img.shields.io/github/forks/Happy591/Serveur_RedEM.svg?style=for-the-badge
[forks-url]: https://github.com/Happy591/Serveur_RedEM/network/members
[stars-shield]: https://img.shields.io/github/stars/Happy591/Serveur_RedEM.svg?style=for-the-badge
[stars-url]: https://github.com/Happy591/Serveur_RedEM/stargazers
[issues-shield]: https://img.shields.io/github/issues/Happy591/Serveur_RedEM.svg?style=for-the-badge
[issues-url]: https://github.com/Happy591/Serveur_RedEM/issues

<a name="readme-top"></a>

<div align="center">

[![Forks][forks-shield]][forks-url] [![Stargazers][stars-shield]][stars-url] [![Issues][issues-shield]][issues-url]

</div>

<br />
<div align="center">
  <a href="https://github.com/Happy591/Base_Serveur_RedEM_FR">
    <img src="images/logo.png" alt="Logo" width="80" height="140">
  </a>

  <h3 align="center">Base de Serveur RedM FR</h3>

  <p align="center">
    Ressource non officielle expliquant les bases pour créer un serveur RedM, et comportant une base de serveur utilisant le framework RedEM.
    <br />
    <a href="https://sinatra.gitbook.io/redemrp/installation"><strong>-> Voir la documatation officielle</strong></a>
    <br />
    <br />
    <a href="https://redm-script-fr.tebex.io/">Mon Tebex</a>
    ·
    <a href="https://discord.gg/gmJeAGNQ">Mon Discord</a>
    ·
    <a href="https://github.com/Happy591/Base_Serveur_RedEM_FR/issues">Signaler un Bug</a>
  </p>
</div>

<details>
  <summary>Sommaire</summary>
  <ol>
    <li>
      <a href="#introduction---framework">Introduction - Framework</a>
      <ul>
        <li>VORP</li>
        <li>REDEM:2023 & REDEM OLD</li>
        <li>RSG</li>
        <li>QBCore</li>
        <li>RPX</li>
        <li>GUM</li>
        <li>BCC</li>
      </ul>
    </li>
    <li>
      <a href="#la-base---le-d%C3%A9veloppement">La Base - Le Développement</a>
      <ul>
        <li>Languages de dévelopement</li>
        <li>Environnement de dévelopement</li>
      </ul>
    </li>
    <li>
      <a href="#installation-de-redm">Installation de RedM</a>
      <ul>
        <li>Tutoriel</li>
        <li>Tutoriel Vidéo</li>
      </ul>
    </li>
    <li>
      <a href="#installation-du-framework">Installation du Framework</a>
      <ul>
        <li>Les Pré-requis</li>
        <li>Créer son projet Git</li>
        <li>Par-feu & Port</li>
        <li>KEY</li>
        <li>Modification de server.cfg</li>
        <li>Base de donnée</li>
        <li>Exécutable</li>
        <li>Tutoriel Vidéo</li>
      </ul>
    </li>
    <li><a href="#maintenir-%C3%A0-jour-son-serveur">Maintenir à Jour son Serveur</a></li>
    <li><a href="#astuces">Astuces</a></li>
    <li><a href="#contribution">Contribution</a></li>
    <li><a href="#support">Support</a></li>
  </ol>
</details>

## Introduction - Framework

<div align="center">
    <img src="https://avatars.githubusercontent.com/u/92413636?s=200&v=4" alt="Logo" width="70" height="70">
    <img src="https://avatars.githubusercontent.com/u/115509535?s=200&v=4" alt="Logo" width="70" height="70">
    <img src="https://bcc-scripts.com/logo_full.png" alt="Logo" width="70" height="70">
    <img src="https://avatars.githubusercontent.com/u/64416274?s=200&v=4" alt="Logo" width="70" height="70">
    <img src="https://avatars.githubusercontent.com/u/58793477?s=200&v=4" alt="Logo" width="70" height="70">
    <img src="https://avatars.githubusercontent.com/u/114295413?s=200&v=4" alt="Logo" width="70" height="70">
    <img src="https://avatars.githubusercontent.com/u/130105567?s=200&v=4" alt="Logo" width="70" height="70">
</div>

Bienvenue sur cette documentation Git qui vous aidera à créer plus facilement la base de votre serveur RedM !

Pour commencer, j'espère que vous êtes armé(e) de patience et de détermination, car, comme vous le découvrirez, le développement d'un serveur n'est ni facile ni rapide... Plusieurs frameworks sur RedM vous proposent des bases pour démarrer votre serveur. Vous y trouverez :

* <b>[VORP Framework](https://discord.gg/DHGVAbCj7N) :</b> VORP est actuellement le framework le plus utilisé, et à juste titre. La base est maintenue à jour très régulièrement et bénéficie d'une grande communauté qui offre un support réactif. Je recommande ce framework aux développeurs débutants, mais aussi à ceux qui souhaitent ouvrir rapidement un serveur. Cependant, le fait qu'il y ait des mises à jour constantes peut être gênant pour ceux qui veulent développer leurs propres scripts, les rendant rapidement obsolètes...

* <b>[RedEM:2023 & RedEM Old Framework](https://discord.gg/nbmTmZR) :</b> RedEM est le deuxième framework le plus utilisé. Il comporte une grande communauté et des mises à jour rares, ce qui rend parfait le développement de vos scripts maison. Attention cependant, même si RedEM permet une plus grande liberté du côté du développement, ce n'est pas pour les développeurs débutants qui manquent de patience, ou si vous voulez ouvrir un serveur rapidement car il vous faudra mettre les mains dans le cambouis.

* <b>[RSG Framework](https://discord.gg/eW3ADkf4Af) :</b> RSG est un jeune framework assez populaire en ce moment, notamment parce que son style est très proche de GTA, ce qui le rend parfait pour les développeurs qui passent d'une plateforme à une autre pour le Roleplay.

* <b>[QBCore Framework](https://discord.gg/qbcore) :</b>  QBCore descend directement du même framework utilisé sur GTA. C'est l'un des plus anciens frameworks sur RedM mais moins populaire désormais.

* <b>[RPX Framework](https://discord.gg/mMNJsDEFp5) :</b> Directement lié au framework RedEM, RPX est un très jeune framework encore en cours de développement qui se veut plus proche du style de GTA.

* <b>[GUM Framework](https://discord.gg/zR9TxRjUfr) :</b> GUM est un framework fait maison par la communauté de développeurs GUM, qu'on retrouve rarement sur des serveurs et qui n'est plus maintenu à jour.

* <b>[BCC Framework](https://discord.gg/bNDpwruqwX) :</b> Enfin, le jeune framework BCC ou Bryce Canyon County est directement lié au framework VORP, puisque ses créateurs ont été de gros contributeurs de VORP avant d'être bannis. Pour le moment, tous leurs scripts sont compatibles avec VORP.

Il ne vous reste plus qu'à faire le choix du framework que vous souhaitez utiliser en fonction de votre temps et de vos compétences en développement.

<p align="right">(<a href="#readme-top">Haut de page</a>)</p>

## La Base - Le Développement

<div align="center">
    <img src="https://i.gifer.com/origin/4d/4d3e7b98dca300caa3365ea6870c8e3d.gif" alt="Logo" width="1000" height="350">
</div>

Cette partie est consacrée aux bases pour commencer ou modifier des scripts dans un environnement idéal, tout en expliquant simplement les différents langages de développement rencontrés lors de la création d'un serveur. Si vous pensiez pouvoir faire du glisser-déposer et jouer sur un serveur RedM parfaitement développé, détrompez-vous. Même si vous achetez des scripts, vous devrez toujours y mettre la main à moins d'avoir un développeur à disposition (un jeune développeur Lua freelance vous coûtera environ 50 euros de l'heure). Donc, envisagez de suivre des cours !

<b><u>Languages de dévelopement</u></b>

<div align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/512px-HTML5_logo_and_wordmark.svg.png" alt="Logo" width="70" height="70">
    <img src="https://i0.wp.com/theicom.org/wp-content/uploads/2016/03/js-logo.png?fit=500%2C500&ssl=1&w=640" alt="Logo" width="70" height="70">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/CSS3_logo_and_wordmark.svg/1452px-CSS3_logo_and_wordmark.svg.png" alt="Logo" width="50" height="70">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/cf/Lua-Logo.svg/2048px-Lua-Logo.svg.png" alt="Logo" width="70" height="70">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/bd/Logo_C_sharp.svg/1200px-Logo_C_sharp.svg.png" alt="Logo" width="60" height="70">
    <img src="https://modern-ti.com/wp-content/uploads/2024/01/sql-database-generic.png" alt="Logo" width="70" height="70">
</div>

* <b>[Lua](https://www.lua.org/)</b> : C'est le langage utilisé partout dans tous les frameworks. Il se rapproche très étroitement de JavaScript tout en étant beaucoup moins complexe que le C#.
* <b>[C#](https://learn.microsoft.com/fr-fr/dotnet/csharp/)</b> : Vous retrouverez du C# dans les anciens scripts des frameworks généralement obsolètes.
* <b>[Javascript](https://www.javascript.com/)</b> : C'est un langage utilisé pour lier les interactions en jeu sur des interfaces à votre script.
* <b>[HTML](https://developer.mozilla.org/fr/docs/Web/HTML)</b> : Permet de structurer une interface.
* <b>[CSS](https://developer.mozilla.org/fr/docs/Web/CSS)</b> : Permet de modifier et de définir le style d'une interface.
* <b>[SQL](https://developer.mozilla.org/fr/docs/Web/CSS)</b> : Permet de sauvegarder des informations dans une base de données.

<b><u>Environnement de dévelopement</u></b>

L'environnement de développement proposé n'est pas obligatoire, mais il vous permettra de commencer votre serveur dans de bonnes conditions.

Dans un premier temps, il vous faut un éditeur de code, car ouvrir le code dans un simple fichier texte risque de vous fatiguer rapidement. Je vous propose donc de télécharger [Visual Code Studio](https://code.visualstudio.com/Download) qui est gratuit et largement suffisant pour votre futur développement. L'avantage avec celui-ci est que vous pouvez ajouter des extensions également gratuites qui vous aideront encore davantage dans votre code. Par exemple, de mon côté, j'utilise :

* <b>[Lua](https://marketplace.visualstudio.com/items?itemName=sumneko.lua)</b> : Permet de générer les erreurs de code du côté LUA.
* <b>[Redm Natives](https://marketplace.visualstudio.com/items?itemName=UnderworldServers.redm-vscode)</b> : Propose des natives de RedM pour vous.
* <b>[HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)</b> : Vous aide du côté HTML et CSS.
* <b>[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)</b> : Ajoute une nouvelle touche de couleur à votre code, le rendant encore plus lisible
* <b>[CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)</b> : Ajoute une nouvelle touche de couleur à votre style, le rendant encore plus lisible.
* <b>[Tabnine AI](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode)</b> : Vous aide à compléter du code en déduisant ce que vous allez écrire.

Il faudra obligatoirement installer [Node](https://nodejs.org/en/) sur votre machine pour pouvoir créer des interfaces dans vos scripts.

Ensuite, il vous faut bien entendu un compte GitHub (si ce n'est pas déjà fait). En effet, il ne faut absolument pas que vous développiez vos ressources uniquement en local, car une simple erreur de clic peut rapidement survenir. Vous allez donc créer un dossier privé dans lequel vous viendrez committer vos modifications. Pour vous éviter d'avoir à utiliser des lignes de commandes dans Visual Studio Code, je vous propose de télécharger la version bureau de [GitHub](https://desktop.github.com/)

Enfin, il va falloir gérer une base de données. C'est pourquoi il vous faudra un éditeur SQL tel que [HEIDI SQL](https://www.heidisql.com/download.php). Cependant, pour que ce logiciel fonctionne, vous devrez installer Apache et SQL sur votre machine qui hébergera votre futur serveur RedM, ou installer [XAMPP](https://www.apachefriends.org/) pour ne pas avoir à installer vous-même Apache et SQL sur votre PC (généralement pas nécessaire si vous avez un serveur virtuel).

<p align="right">(<a href="#readme-top">Haut de page</a>)</p>

## Installation de RedM

<b><u>Tutoriel</u></b>

<div align="center">
    <img src="https://www.breakflip.com/uploads2/Slash/AAA/vignette-rdr2-rp-comment-faire.jpg" alt="Logo" width="600" height="350">
</div>

Dans un premier temps, rendez-vous sur le site internet officiel [RedM](https://redm.net/) et cliquez ensuite sur "Download Client" afin de télécharger l'exécutable.

<div align="center">
    <img src="https://wikiredm.redstartrp.fr/unknown2.png" alt="Logo" width="600" height="400">
</div>

Avant de lancer l'exécutable, pensez à démarrer votre launcher Rockstar Games. Ensuite, exécutez le fichier RedM.exe. Après une courte période, RedM vous demandera de choisir le .exe de RDR2 pour bien relier RedM à votre jeu. Vous recevrez ensuite une demande de mise à jour du cache de votre jeu, acceptez-la et le téléchargement de RedM se lancera. *

<div align="center">
    <img src="https://wikiredm.redstartrp.fr/unknown3.png" alt="Logo" width="600" height="400">
</div>

Le temps de téléchargement varie énormément en fonction des personnes et de différents paramètres tels que les performances de l'ordinateur, votre connexion internet ou RedM lui-même. Comptez donc entre 1 heure et 4 heures, voire 15 heures... 

<div align="center">
    <img src="https://wikiredm.redstartrp.fr/unknown5.png" alt="Logo" width="400" height="150">
</div>

Une fois le téléchargement terminé, vous pouvez enfin lancer RedM.

<b><u>Tutoriel Vidéo</u></b>

_Work in progress..._

<p align="right">(<a href="#readme-top">Haut de page</a>)</p>

## Installation du Framework

<div align="center">
    <img src="https://i.ytimg.com/vi/x8SsgBpkcxI/sddefault.jpg" alt="Logo" width="440" height="340">
</div>

Si vous estimez que le framework parfait pour vous est RedEM, alors c'est parfait, vous pouvez continuer à lire cette partie. Sinon, je vous invite à suivre la procédure d'installation des autres frameworks. N'oubliez pas également que cette base n'est pas une ressource officielle. Elle devra également être mise à jour par vos soins lors de nouvelles mises à jour du framework RedEM. Vous devez également apporter certaines modifications aux fichiers indiqués pour pouvoir lancer votre serveur.

<b><u>Les Pré-requis</u></b>

Il est <b>INDISPENSABLE</b> d'avoir les éléments suivants avant de commencer l'installation d'un framework, sans quoi votre procédure d'installation sera vouée à l'échec.

* Avoir [Red Dead Redmemption 2](https://www.rockstargames.com/fr/games/reddeadredemption2) ou [Red Dead Online](https://www.rockstargames.com/fr/reddeadonline)
* Être connecté sur [Steam](https://store.steampowered.com/?l=french)
* Être connecté sur le [Rockstar Games Launcher](https://socialclub.rockstargames.com/rockstar-games-launcher)
* Avoir installé [RedM](https://redm.net/) sur sa machine.

<b><u>Créer son projet Git</u></b>

Dans un premier temps, dans un dossier de préférence situé à la racine de votre disque, que vous pouvez nommer comme bon vous semble, importez le fork du projet Git principal en exécutant la commande associée dans une console de commande :

```sh
git clone https://github.com/Happy591/Base_Serveur_RedEM_FR.git
```

<b><u>Par-feu & Port</u></b>

Voici le principal problème auquel vous pourriez être confronté : comment ouvrir les ports pour FXServer ? Normalement, il suffit de suivre les étapes suivantes :

* Ouvrez le Pare-feu Windows Defender avec les fonctions avancées de sécurité.
* Accédez aux règles de trafic entrant.
* Créez une nouvelle règle avec les options suivantes : Port, TCP avec des ports locaux spécifiques : 30120, Autoriser la connexion, Domaine Privé et Public, Nom : 30120 TCP.
* Répétez l'étape 3, mais sélectionnez UDP comme protocole de port, puis Nom : 30120 UDP.
* Effectuez un Ipconfig où vous copierez l'adresse passerelle dans votre navigateur. En fonction de votre fournisseur d'accès internet, accédez à NAT et ouvrez le port 30120 (une adresse IP statique de la machine est requise).
* Répétez toutes ces étapes pour ouvrir le port 40120 (pour pouvoir accéder à TxAdmin depuis un autre poste).

Le problème ici, c'est qu'il est impossible pour certains opérateurs de changer les paramètres NAT (exemple : SFR) ou alors vous devrez changer votre abonnement Internet pour pouvoir le faire, moyennant des frais supplémentaires (exemple : Orange). La seule solution dans ce cas est de louer une machine virtuelle pour héberger votre serveur.

<b><u>KEY</u></b>

Chaque serveur a deux clés uniques que vous devrez générer.

* Sur Steam, elle se nomme [API KEY](https://steamcommunity.com/dev/apikey)
* Sur RedM, elle se nomme [KEYMASTER](https://keymaster.fivem.net/server/)

Il va falloir créer votre compte sur le forum [CFX](https://forum.cfx.re/) si ce n'est pas déjà fait pour obtenir la KEYMASTER. Rappelez-vous bien de vos identifiants, ils vous seront utiles dans le futur. Une fois fait, rendez-vous sur le lien ci-dessus, cliquez sur "New Server" et remplissez le formulaire en fonction de vos paramètres. Une fois terminé, copiez le code de votre clé, nous nous en resservirons.

<b><u>Modification de server.cfg</u></b>

Dans le fichier server.cfg situé dans le dossier Serveur_RedEM/server-data/server.cfg, vous devrez modifier les clés uniques par celles que vous avez générées un peu plus tôt, mais également remplacer les adresses IP par celle de votre machine.
* Ligne 19 
```js
endpoint_add_tcp "TON.IP:30120"
```
* Ligne 20 
```js
endpoint_add_udp "TON.IP:30120"
```
* Ligne 83
```js
set steam_webApiKey "APIKEY"
``` 
* Ligne 86
```js
sv_licenseKey "KEYMASTER"
```

**N'oubliez pas de sauvegarder les modifications !**

<b><u>Base de donnée</u></b>

MariaDB est le système de gestion de base de données utilisé. Pour assurer le bon fonctionnement du serveur, il est donc nécessaire de démarrer la base de données associée.

* Lancez XAMPP et démarrez Apache et MySQL.
* Lancez HEIDI SQL et créez votre session avec le nom que vous souhaitez.
* Lancez la session, créez une nouvelle base de données que vous nommerez redemrp.
* Une fois à l'intérieur, celle-ci est vide, allez dans "File" puis "Run SQL file..." et exécutez le fichier RedEM_PreBuild.sql situé dans Serveur_RedEM/server-sql/RedEM_PreBuild.sql.

**Ignorez les avertissements s'il y en a !**

<b><u>Exécutable</u></b>

Une fois toutes ces opérations terminées, lancez FXServer.exe situé dans Serveur_RedEM/server/FXServer.exe. Une console s'affichera à l'écran et vous serez redirigé vers une nouvelle page web pour installer TX Admin. Assurez-vous de choisir le chemin pour votre fichier ici : Serveur_RedEM/server-data/server.cfg, pas besoin d'en créer un nouveau. Après un court délai d'attente, une fois que le cache est installé et après avoir relancé votre exécutable, vous pourrez enfin vous connecter au serveur !

Vous devez être connecté à RedM ainsi qu'à votre licence avec le même compte pour bénéficier des permissions administratives.

<b><u>Tutoriel Vidéo</u></b>

_Work in progress..._

<p align="right">(<a href="#readme-top">Haut de page</a>)</p>

## Maintenir à Jour son Serveur

Il va de soi que pour maintenir son framework à jour, il est essentiel d'être sur le discord de celui-ci ([Discord de RedEM](https://discord.gg/nbmTmZR)). Cependant, ce n'est pas tout : il faut également se tenir informé des mises à jour de TXAdmin ([Discord de TXAdmin](https://discord.gg/yWxjt9zPWR)) et de CFX ([Discord de CFX](https://discord.gg/fivem)).

Régulièrement, il faudra également vous rendre sur cette ([page](https://runtime.fivem.net/artifacts/fivem/build_server_windows/master/)) et télécharger le dernier artifact.

<div align="center">
    <img src="https://zupimages.net/up/24/11/j6x1.png" alt="Logo" width="1000" height="350">
</div>

Ensuite, vous devrez dézipper son contenu dans le dossier server de votre base RedM. Si vous ne savez pas quand vous devez mettre à jour l'artefact de votre serveur, vous pouvez le voir lorsque vous vous connectez dessus. En effet, vous verrez à droite une notification indiquant que l'artefact est outdated, de couleur blanche, jaune ou rouge. Vous imaginez bien qu'au plus la couleur se rapproche du rouge, au plus votre serveur nécessite une mise à jour rapidement.

<div align="center">
    <img src="https://forum.cfx.re/uploads/default/original/4X/1/2/f/12f0dbf604e661838f6c0d893be03e3c37f13b06.png" alt="Logo" width="450" height="300">
</div>

<p align="right">(<a href="#readme-top">Haut de page</a>)</p>

## Astuces

* Dans les paramètres graphiques de votre jeu, mettez-vous en DirectX et non en VULKAN, cela vous évitera certains crashs de RedM.
* Consultez régulièrement les forums RedM de [CFX](https://forum.cfx.re/c/redm-development/redm-releases/60) pour y trouver de nouveaux scripts.
* Soyez sur le plus de discords de créateurs possible, certains offrent des ressources gratuites pour votre serveur.
* Soyez sur le discord de tous les frameworks pour récupérer des ressources gratuites et recevoir de l'aide.
* La plupart des choses que vous souhaitez créer sont disponibles gratuitement, il suffit juste de bien fouiller pour les trouver.
* Le monde du MLO est un autre style de développement particulier, ne vous lancez pas dans le développement de scripts et dans le développement d'MLO, vous allez vite vous décourager. Alors, rendez-vous sur le discord de [Spooni](https://discord.com/invite/t2NWABD6QJ) qui propose actuellement les meilleurs mappages de RedM.
* Il vaut mieux payer un peu plus cher un script et l'avoir en open source que lock. Ainsi, vous pourrez apprendre la logique de code des autres pour vous améliorer.
* Méfiez-vous des créateurs, n'achetez jamais un script via PayPal et regardez dans les différents discords s'il ne figure pas dans la liste des mauvais développeurs.
* Persévérez pour ouvrir un bon serveur, même avec beaucoup d'argent, vous prendra au moins une bonne année.

<p align="right">(<a href="#readme-top">Haut de page</a>)</p>

## Contribution

Les contributions font avancer le projet plus vite qu'une personne seule. Toutes les contributions que vous faites sont donc **grandement appréciées**. Si vous avez une suggestion qui améliorerait le projet, n'hésitez pas à créer une demande de fork.

N'oubliez pas de mettre une étoile au projet ! Merci !

1. Fork le Projet
2. Créer une Branch par feature (`git checkout -b feature/NomdeFeature`)
3. Commiter vos Changements (`git commit -m 'Description de feature'`)
4. Push vers la Branch (`git push origin feature/NomdeFeature`)
5. Ouvrir une requête Pull

<p align="right">(<a href="#readme-top">Haut de page</a>)</p>

## Support

* Pour obtenir plus d'assistance sur d'éventuels problèmes avec le framework RedEM, consultez leur serveur [discord](https://discord.gg/FKH4uwb)<br />
* Pour obtenir plus d'assistance sur d'éventuels problèmes avec CFX, consultez leur serveur [discord](https://discord.gg/fivem)<br />
* Pour obtenir plus d'assistance sur d'éventuels problèmes avec TxAdmin, consultez leur serveur [discord](https://discord.gg/yWxjt9zPWR)<br />

<p align="right">(<a href="#readme-top">Haut de page</a>)</p>