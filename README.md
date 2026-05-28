# cybersecurity Curated Readings
Une liste de sites internet, articles et autres ressources concernant la cybersecurité.  
La pluspart de ces ressources sont gratuites ou nécessitent la création d'un compte utilisateur offrant un accès à des fonctionnalités limitées mais utiles.

## :newspaper_roll: Informations
> A news a day, a CISO some day  
### Generaliste
- :fr: [clubic](https://www.clubic.com) : Informations tech, e-commerce, sciences, cyber, ...
- :fr: [numerama](https://www.numerama.com/) : Infos sur les thèmes tech, société, pop culture, sciences, cyber, ...
- :fr: [Data Security Breach](https://www.datasecuritybreach.fr/) : Infos cybersécurité, fuite de données, CTI, ... (édité par ZATAZ)
- :gb: [wired](https://www.wired.com/category/security/) : référence internationale tech et cyber
- :gb: [PC Mag](https://www.pcmag.com/) : Infos généralistes
- :gb: [cybernews](https://cybernews.com/) : Infos securité, cybercrime, crypto, tech, ...
- :gb: [cybersecuritynews.com](https://cybersecuritynews.com/) : Infos menaces, cyber attaques, vulnérabilités, fuites de données, ...
- :gb: [hackread.com](https://hackread.com/latest/) : informations, tech, securité, crypto, IA, ...
- :gb: [thecyberexpress.com](https://thecyberexpress.com/) : Une foule d'infos intéressantes, y compris en matière de conformité et gouvernance
- :gb: [reuters.com](https://www.reuters.com/technology/cybersecurity/) : Edition de l'agence Reuters, catégorie cybersécurité
- :fr: [korben.info](https://korben.info/) : infos généralistes

### Fuite de données, OSINT, ...
- :fr: [zataz](https://www.zataz.com) : Toutes les dernières infos en ce qui concerne les fuites de données. Comprend également quelques outils intéressants de sensibilisation et de diagnostics

### Inclassable
- :fr: [it-connect](https://www.it-connect.fr/) : comprend des tutoriaux IT (dont cybersécurité), des news et autres ressources

## :eyeglasses: OSINT / Cyber Threat Intelligence (OSINT)
> 
- :gb: [dehashed](https://dehashed.com/) : permet de rechercher, selon différents critères, la présente d'informations dans des fuites de données (email, domaine, hash de mot de passe, ...)
- :gb: [socradar.io](https://socradar.io/) : génère, à partir d'un domaine ou adresse email, un rapport contenant les fuites d'identifiants, les logs volés présents sur le web, mentions sur le darkweb
- :gb: [worldmonitor](https://worldmonitor.app/) : une application en ligne qui aggrège une grande source d'informations. Comprend aussi des flux vidéos et une carte interactive géolocalisant les événements. Assez lourd en terme de ressources.

### Outils
- :gb: [shadowdragon.io](https://shadowdragon.io/free-osint-tools/) : outils gratuits relatifs à l'OSINT (checklist generator, Google Dork Assistant, email permutator, image forensics, ...)
- :gb: [OSINT framework](https://osintframework.com/) : Framework permettant, en fonction des informations recherchées, d'identifier les outils appropriés.
 - :gb: [Hunchly](https://hunch.ly/) : un outil pour créer vos *cases* OSINT et conserver vos *findings*. Recommandé par ZATAZ et édité par Maltego
 - :gb: [](https://tools.osintnewsletter.com/) : Compilation d'outils OSINT classés par catégories.

## :pirate_flag: Hacking
> Defense by offense
### Pentesting et hacking
- :gb: [thehacker.recipes](https://www.thehacker.recipes/) : probablement l'un des sites les plus intéressants pour apprendre la démarche de compromission d'un système d'informations
- :gb: [Hackaday](https://hackaday.com/) : Spécialisé en "hardware hacking" 

### Outils
- :gb: [Exegol](https://exegol.com/) : Une suite de plus de 400 outils de pentesting qui peut s'intégrer à votre OS. Basé sur pipx. Les outils sont indépendants (containerisés) et fonctionnels en permanence. Edité par des français :rooster:

## :toolbox: Autres outils
> Parce que vous n'êtes pas MacGyver...
### OS Systèmes d'exploitation
- :gb: [NixOS](https://nixos.org/) : Un OS avec un gros potentiel pour la cybersécurité. Sert de base à [Securix](https://github.com/cloud-gouv/securix/tree/main) et [Bureautix](https://github.com/cloud-gouv/bureautix-example) de la [DINUM](https://www.numerique.gouv.fr/numerique-etat/dinum/)
- :fr: [Hackix](https://github.com/snurit/Hackix) : un embryon d'OS pour les auditeurs et pentesters. Comprend un mode OSINT (tout en RAM. KDE plasma 6), pentest (environnement [hyprland](https://hypr.land/), forensique (en RAM. Environnement XFCE) et un environnement général (KDE plasma 6) pour la rédaction des rapports d'audit.
- :gb: [ParrotSec OS](https://parrotsec.org/) : Parrot Security OS - similaire à Kali linux
- :gb: [Kali](https://www.kali.org/) : Kali linux security
### Aggrégateurs d'informations
- :gb: [Feedly](https://feedly.com/) : Aggrégation de liens RSS et sources d'informations
- :gb: [Flipboard](https://flipboard.com/) : Aggrégation de liens RSS et sources d'informations
### GRC
- :fr: [CISO Assistant](https://intuitem.com/fr/ciso-assistant/) : Outil d'audit GRC assez complet. Plusieurs modes de fonctionnement dont un containerisé. :rooster:
### Sécurisation de l'AD
- :gb: [Ping Castle](https://www.pingcastle.com/) : Audit de sécurité Windows pour environnements AD
- :gb: [Purple Knight](https://www.semperis.com/purple-knight) : Un outil complémentaire à Ping Castle
- :gb: [GPOZaurr](https://github.com/EvotecIT/GPOZaurr) : Audit des GPO de l'AD pour trouver les GPo orphelines, problèmes de cohérences, mots de passes dans GPO, ...
### SOC
- :gb: [IBM X-Force Exchange](https://exchange.xforce.ibmcloud.com/) : Suite d'outils pour la qualification d'artefacts (nom d'application, adresse IP, URL, hash MD5, ...). Similaire à *VirusTotal*
- :gb: [VirusTotal](https://www.virustotal.com/gui/home/upload) : Outil d'analyse de fichiers, URL et autres artefacts pour qualifier une possible menace. Similaire à *IBM X-Force Exchange*
- :gb: [AbuseIPDB](https://www.abuseipdb.com) : base de données d'adresse IP malveillante. Permet à la fois de rechercher si une IP est dans la base et de signaler une IP malveillante.