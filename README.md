<p align="center">
  <img src="https://github.com/alizealebaron/alizealebaron/blob/main/assets/netPractice.png" width="120"/>
</p>
<h3 align="center">
  <em>How to configure small-scale networks ?</em>
</h3>

---

<div align="center">
  <p>
      <!-- <img src="https://img.shields.io/badge/score-125%20%2F%20100-success?style=for-the-badge" /> -->
      <img src="https://img.shields.io/github/languages/count/alizealebaron/netPractice?style=for-the-badge&logo=" />
      <img src="https://img.shields.io/github/languages/top/alizealebaron/netPractice?style=for-the-badge" />
      <img src="https://img.shields.io/github/last-commit/alizealebaron/netPractice?style=for-the-badge" />
  </p>
</div>

## ⚠️ Avant propos

- **Portfolio :** Ce répertoire se concentre sur un seul sujet. Vous pouvez retrouver tous mes projets sur mon [profil](https://github.com/alizealebaron).
- **Sujet :** Conformément aux règles de 42, vous ne trouverez pas le sujet de l'exercice dans ce répertoire.
- **État du projet:** Le code est exactement le même que lorsqu'il a été validé. Il ne sera pas mis à jour même s'il contient des erreurs.
- **Aide & Licence :** Ce répertoire est principalement là pour vous aider à faire votre propre code. Évitez de copier / coller sans comprendre le code.

## 🦆 Status

**Commencé le :** 15/06/2026

**Rendu le :** Non rendu.

## Description

**NetPractice** est un exercice pratique général conçu pour introduire aux bases du réseau informatique. L'objectif principal de ce projet est de configurer de petits réseaux simulés afin de les rendre pleinement fonctionnels. 

À travers 10 niveaux d'exercices progressifs, ce projet permet de comprendre et de mettre en pratique:
* L'adressage **TCP/IP**.
* La configuration des **masques de sous-réseau**.
* L'interconnexion d'appareils via des **routeurs** et des **switchs**.

## Instructions

### Lancement de l'interface

Le projet s'exécute sur une interface d'entraînement simulée accessible depuis un navigateur web. Pour la lancer :

1. Téléchargez le fichier compressé joint à la page du projet et extrayez-le dans le dossier de votre choix.
2. Exécutez le script réseau local depuis votre terminal :
```bash
   sh run.sh
```

Alternative manuelle : En cas de dysfonctionnement du script dû aux contraintes de sécurité des navigateurs, vous pouvez lancer manuellement un serveur Python: 
```bash
python3 -m http.server 49242
```

3. Naviguez ensuite sur http://localhost:49242. (où 49242 est le port que vous avez défini).

### Utilisation de l'interface et validation

1. Entrez votre login de l'intranet dans le champ dédié pour charger votre configuration personnelle (ou utilisez l'onglet "Evaluation" pour générer un réseau aléatoire).
2. Résolvez les objectifs affichés en haut de l'écran en modifiant uniquement les champs non grisés du diagramme.
3. Utilisez le bouton [Check again] pour vérifier si votre configuration réseau est correcte.
4. Les journaux (logs) affichés en bas de page vous aideront à diagnostiquer les erreurs (passerelle manquante, IP invalide, etc.).

### Exportation et Rendu

1. À chaque fois qu'un niveau est validé avec succès, vous devez impérativement cliquer sur le bouton [Get my config] pour télécharger le fichier de configuration du niveau avant de passer au suivant.
2. Le dépôt Git final doit contenir exactement 10 fichiers de configuration exportés (un fichier par niveau validé), placés directement à la racine (root) de votre dépôt.

## Ressources

## Documentation sur la configuration d'un réseau

- [Le routage IP statique](https://fr.wikibooks.org/wiki/R%C3%A9seaux_TCP/IP/Le_routage_IP_statique)
- [TCP/IP Addressing](https://web.archive.org/web/20221003073118/https://sites.ualberta.ca/dept/chemeng/AIX-43/share/man/info/C/a_doc_lib/aixbman/commadmn/tcp_address.htm)
- [Adresses IPv4 et le calcul des masques de sous-réseaux](https://www.it-connect.fr/adresses-ipv4-et-le-calcul-des-masques-de-sous-reseaux/)
- [Qu’est ce qu’un switch informatique ?](https://talice.com/actualites/quest-ce-quun-switch)
- [IP address](https://en.wikipedia.org/wiki/IP_address)

## Utilisation de l'IA

- Relecture et traduction en anglais du README

---

**Dernière modification:** 17 juin 2026\
**Contact :** alebaron@student.42lehavre.fr
