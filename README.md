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
      <a href="#a-propros-de-la-base-">Introduction - Framework</a>
    </li>
    <li>
      <a href="#a-propros-de-la-base-">La Base - Le Développement</a>
      <ul>
        <li><a href="#languages-et-environnement-de-d%C3%A9velopement-utilis%C3%A9-">Languages de dévelopement</a></li>
        <li><a href="#languages-et-environnement-de-d%C3%A9velopement-utilis%C3%A9-">Environnement de dévelopement</a></li>
      </ul>
    </li>
    <li>
      <a href="#installation-">Installation du Framework</a>
      <ul>
        <li><a href="#pr%C3%A9-requis-">Les Pré-requis</a></li>
        <li><a href="#t%C3%A9l%C3%A9chargement-">Créer son projet Git</a></li>
        <li><a href="#extension-de-vs-code-">Par-feu & Port</a></li>
        <li><a href="#cr%C3%A9er-son-projet-git-">KEY</a></li>
        <li><a href="#par-feu--port-">Modification de server.cfg</a></li>
        <li><a href="#key-">Base de donnée</a></li>
        <li><a href="#modification-de-servercfg-">Exécutable</a></li>
        <li><a href="#base-de-donn%C3%A9e-">Tutoriel </a></li>
      </ul>
    </li>
    <li><a href="#contribution-">Maintenir à Jour son Serveur</a></li>
    <li><a href="#contribution-">Astuces</a></li>
    <li><a href="#contribution-">Contribution</a></li>
    <li><a href="#license-">License</a></li>
    <li><a href="#support-">Support</a></li>
  </ol>
</details>

## Introduction - Framework

<div align="center">
  <a href="https://github.com/Happy591/Base_Serveur_RedEM_FR">
    <img src="https://w0.peakpx.com/wallpaper/20/49/HD-wallpaper-red-dead-redemption-2-2021-red-dead-redemption-2-games-2021-games.jpg" alt="Logo" width="1000" height="400">
  </a>
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

Cette partie est consacrée aux bases pour commencer ou modifier des scripts dans un environnement idéal, tout en expliquant simplement les différents langages de développement rencontrés lors de la création d'un serveur. Si vous pensiez pouvoir faire du glisser-déposer et jouer sur un serveur RedM parfaitement développé, détrompez-vous. Même si vous achetez des scripts, vous devrez toujours y mettre la main à moins d'avoir un développeur à disposition (un jeune développeur Lua freelance vous coûtera environ 50 euros de l'heure). Donc, envisagez de suivre des cours !

<b><u>Languages de dévelopement</u></b>

* [Lua](https://www.lua.org/) : C'est le langage utilisé partout dans tous les frameworks. Il se rapproche très étroitement de JavaScript tout en étant beaucoup moins complexe que le C#.
* [C#](https://learn.microsoft.com/fr-fr/dotnet/csharp/) : Vous retrouverez du C# dans les anciens scripts des frameworks généralement obsolètes.
* [Javascript](https://www.javascript.com/) : C'est un langage utilisé pour lier les interactions en jeu sur des interfaces à votre script.
* [HTML](https://developer.mozilla.org/fr/docs/Web/HTML) : Permet de structurer une interface.
* [CSS](https://developer.mozilla.org/fr/docs/Web/CSS) : Permet de modifier et de définir le style d'une interface.
* [SQL](https://developer.mozilla.org/fr/docs/Web/CSS) : Permet de sauvegarder des informations dans une base de données.

<b><u>Environnement de dévelopement</u></b>

L'environnement de développement proposé n'est pas obligatoire, mais il vous permettra de commencer votre serveur dans de bonnes conditions.

Dans un premier temps, il vous faut un éditeur de code, car ouvrir le code dans un simple fichier texte risque de vous fatiguer rapidement. Je vous propose donc de télécharger [Visual Code Studio](https://code.visualstudio.com/Download) qui est gratuit et largement suffisant pour votre futur développement. L'avantage avec celui-ci est que vous pouvez ajouter des extensions également gratuites qui vous aideront encore davantage dans votre code. Par exemple, de mon côté, j'utilise :

* [Lua](https://marketplace.visualstudio.com/items?itemName=sumneko.lua) : Permet de générer les erreurs de code du côté LUA.
* [Redm Natives](https://marketplace.visualstudio.com/items?itemName=UnderworldServers.redm-vscode) : Propose des natives de RedM pour vous.
* [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css) : Vous aide du côté HTML et CSS.
* [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) : Ajoute une nouvelle touche de couleur à votre code, le rendant encore plus lisible
* [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek) : Ajoute une nouvelle touche de couleur à votre style, le rendant encore plus lisible.
* [Tabnine AI](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode) : Vous aide à compléter du code en déduisant ce que vous allez écrire.

Il faudra obligatoirement installer [Node](https://nodejs.org/en/) sur votre machine pour pouvoir créer des interfaces dans vos scripts.

Ensuite, il vous faut bien entendu un compte GitHub (si ce n'est pas déjà fait). En effet, il ne faut absolument pas que vous développiez vos ressources uniquement en local, car une simple erreur de clic peut rapidement survenir. Vous allez donc créer un dossier privé dans lequel vous viendrez committer vos modifications. Pour vous éviter d'avoir à utiliser des lignes de commandes dans Visual Studio Code, je vous propose de télécharger la version bureau de [GitHub](https://desktop.github.com/)

Enfin, il va falloir gérer une base de données. C'est pourquoi il vous faudra un éditeur SQL tel que [HEIDI SQL](https://www.heidisql.com/download.php). Cependant, pour que ce logiciel fonctionne, vous devrez installer Apache et SQL sur votre machine qui hébergera votre futur serveur RedM, ou installer [XAMPP](https://www.apachefriends.org/) pour ne pas avoir à installer vous-même Apache et SQL sur votre PC (généralement pas nécessaire si vous avez un serveur virtuel).

<p align="right">(<a href="#readme-top">Haut de page</a>)</p>

## Installation du Framework

Si vous estimez que le framework parfait pour vous est RedEM, alors c'est parfait, vous pouvez continuer à lire cette partie. Sinon, je vous invite à suivre la procédure d'installation des autres frameworks. N'oubliez pas également que cette base n'est pas une ressource officielle. Elle devra également être mise à jour par vos soins lors de nouvelles mises à jour du framework RedEM. Vous devez également apporter certaines modifications aux fichiers indiqués pour pouvoir lancer votre serveur.

<b><u>Les Pré-requis</u></b>

Il est <b>INDISPENSABLE</b> d'avoir les éléments suivants avant de commencer l'installation d'un framework, sans quoi votre procédure d'installation sera vouée à l'échec.

* Avoir [Red Dead Redmemption 2](https://www.rockstargames.com/fr/games/reddeadredemption2) ou [Red Dead Online](https://www.rockstargames.com/fr/reddeadonline)
* Être connecté sur [Steam](https://store.steampowered.com/?l=french)
* Être connecté sur le [Rockstar Games Launcher](https://socialclub.rockstargames.com/rockstar-games-launcher)

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

Le problème ici, c'est qu'il est impossible pour certains opérateurs de changer les paramètres NAT (coucou à SFR :clown_face) ou alors vous devrez changer votre abonnement Internet pour pouvoir le faire, moyennant des frais supplémentaires (coucou à Orange :clown_face:). La seule solution dans ce cas est de louer une machine virtuelle pour héberger votre serveur.

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

_Dans le futur..._

<p align="right">(<a href="#readme-top">Haut de page</a>)</p>



















## Maintenir à Jour son Serveur

Il va de soi que pour maintenir son framework à jour, il est essentiel d'être sur le Discord de celui-ci. Cependant, ce n'est pas tout : il faut également se tenir informé des mises à jour de TXAdmin et de CFX. Régulièrement, il faudra aussi vous rendre sur cette page et télécharger le dernier artifact, que vous dézipperez ensuite dans le dossier du server.

https://runtime.fivem.net/artifacts/fivem/build_server_windows/master/


## Astuces

Forum cfx
discord chercher



[![Product Name Screen Shot][product-screenshot]](https://github.com/orgs/RedEM-RP/repositories)


## Contribution :

Les contributions font avancer le projet plus vite qu'une personne seule. Toutes les contributions que vous faites sont donc **grandement appréciées**. Si vous avez une suggestion qui améliorerait le projet, n'hésitez pas à créer une demande de fork.

N'oubliez pas de mettre une étoile au projet ! Merci !

1. Fork le Projet
2. Créer une Branch par feature (`git checkout -b feature/NomdeFeature`)
3. Commiter vos Changements (`git commit -m 'Description de feature'`)
4. Push vers la Branch (`git push origin feature/NomdeFeature`)
5. Ouvrir une requête Pull

<p align="right">(<a href="#readme-top">Haut de page</a>)</p>

## License :

Distribué sous la GNU License. Voir `LICENSE.txt` pour plus d'informations.

<p align="right">(<a href="#readme-top">Haut de page</a>)</p>

## Support :

Pour plus assistance sur de potentiels problèmes avec le framework consultez leur [discord](https://discord.gg/FKH4uwb)<br />
Pour plus assistance sur de potentiels problèmes avec CFX consultez leur [discord](https://discord.gg/fivem)<br />
Pour plus assistance sur de potentiels problèmes avec TxAdmin consultez leur [discord](https://discord.gg/yWxjt9zPWR)<br />

<p align="right">(<a href="#readme-top">Haut de page</a>)</p>



