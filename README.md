<p align="center">
  <img src="assets/branding/ncore-control-official.jpg" alt="NCore Control official logo" width="380">
</p>

<h1 align="center">NCore Control</h1>

<p align="center"><strong>Application Windows officielle pour installer et gérer des serveurs NANOS / nanos world.</strong></p>

<p align="center">
  <a href="https://github.com/ncore-framework-official/ncore-control/releases/download/control-v1.0.0/NCore-Control-Setup-1.0.0.exe">
    <img src="https://img.shields.io/badge/Télécharger-1.0.0-17C0E4?style=for-the-badge&logo=windows&logoColor=white" alt="Télécharger NCore Control 1.0.0">
  </a>
  <a href="https://github.com/ncore-framework-official/ncore-control/releases/tag/control-v1.0.0">
    <img src="https://img.shields.io/badge/Release-stable-2EA043?style=for-the-badge" alt="Stable release">
  </a>
  <a href="https://discord.gg/Ey4dn4Cbqj">
    <img src="https://img.shields.io/badge/Discord-Officiel-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord officiel">
  </a>
</p>

> **Version publique actuelle : NCore Control 1.0.0 — Windows x64.**  
> La release officielle est désormais publiée dans ce dépôt. La release historique reste également disponible à son ancienne URL afin de préserver tous les liens déjà distribués et le canal de mise à jour existant.

## Français

### Ce que fait NCore Control

NCore Control centralise l'installation et la gestion de serveurs NANOS / nanos world dans une application Windows dédiée.

Fonctions livrées dans la version 1.0.0 :

- installer un serveur NANOS / nanos world standard ;
- gérer plusieurs instances serveur indépendantes ;
- démarrer et arrêter les serveurs gérés ;
- faire fonctionner plusieurs serveurs distincts indépendamment ;
- créer un raccourci Bureau dédié pour chaque serveur ;
- supprimer de manière ciblée un serveur géré et son raccourci ;
- gérer les mises à jour de NCore Control ;
- utiliser une installation et une désinstallation Windows avec interface visible ;
- conserver les fichiers et données des serveurs NANOS lors de la désinstallation de NCore Control.

### Installation

1. Téléchargez **[NCore-Control-Setup-1.0.0.exe](https://github.com/ncore-framework-official/ncore-control/releases/download/control-v1.0.0/NCore-Control-Setup-1.0.0.exe)**.
2. Lancez l'installateur Windows.
3. Démarrez NCore Control depuis son raccourci Bureau ou les applications installées.
4. Choisissez le type de serveur et la destination, vérifiez la destination puis lancez l'installation.

L'installation automatique de **NCore Framework** n'est pas activée dans NCore Control 1.0.0.

### Gestion multi-serveur

NCore Control permet de gérer plusieurs serveurs NANOS / nanos world comme des instances indépendantes. Une action ciblée sur un serveur ne doit pas modifier les autres instances.

La version publique 1.0.0 permet notamment :

- plusieurs installations serveur distinctes ;
- démarrage et arrêt ciblés ;
- plusieurs processus serveur actifs indépendamment ;
- raccourcis Bureau distincts ;
- suppression ciblée d'une instance gérée.

Les limites CPU, mémoire, disque et réseau restent celles de la machine hôte.

### Mises à jour

NCore Control 1.0.0 possède un canal de mise à jour stable.

Le fichier ZIP :

`NCore-Control-1.0.0-win-x64.zip`

est le payload technique utilisé par le canal de mise à jour et **n'est pas le parcours normal d'installation manuelle**.

Les URL historiques du canal 1.0.0 restent volontairement conservées afin de ne pas casser les installations existantes. La distribution utilisateur de référence est désormais la release officielle de ce dépôt : https://github.com/ncore-framework-official/ncore-control/releases/tag/control-v1.0.0.

### Intégrité des téléchargements

SHA-256 officiels de la release 1.0.0 :

```text
NCore-Control-Setup-1.0.0.exe
5bf8e8a47df6d45272844edf2e5fb5410e93977b2af7b909def1c8b3f4069f06

NCore-Control-1.0.0-win-x64.zip
f12989e4ea1598225f2ac0b41f03f470b00d2dfd55e4c6a84ed9b1a3cde48a72
```

Voir également [CHECKSUMS.txt](CHECKSUMS.txt).

### NCore Framework

NCore Control et NCore Framework sont deux produits liés mais distincts.

La version 1.0.0 de NCore Control installe et gère des serveurs NANOS standards. L'installation automatique du Framework RP NCore n'est pas encore activée dans cette release.

### Support

- **Discord officiel :** https://discord.gg/Ey4dn4Cbqj
- **Organisation publique NCore :** https://github.com/ncore-framework-official
- **Release 1.0.0 :** https://github.com/ncore-framework-official/ncore-control/releases/tag/control-v1.0.0
- **Support public :** voir [SUPPORT.md](SUPPORT.md)

---

## English

**NCore Control** is the official Windows application for installing and managing NANOS / nanos world servers.

### Current public release

**NCore Control 1.0.0** is the first public stable release for Windows x64.

Main features:

- install a standard NANOS / nanos world server;
- manage multiple independent server instances;
- start and stop managed servers;
- operate several managed servers independently;
- create a dedicated desktop shortcut for each managed server;
- remove a selected managed server and its shortcut;
- manage NCore Control updates;
- preserve existing NANOS server files and data when NCore Control itself is uninstalled.

Automatic installation of **NCore Framework** is not enabled in NCore Control 1.0.0.

For normal installation, use **[NCore-Control-Setup-1.0.0.exe](https://github.com/ncore-framework-official/ncore-control/releases/download/control-v1.0.0/NCore-Control-Setup-1.0.0.exe)**.

The ZIP archive is the technical update payload, not the normal manual installation path.

The official organization release is https://github.com/ncore-framework-official/ncore-control/releases/tag/control-v1.0.0. The original historical release remains available for compatibility with links and update channels already distributed.

Official SHA-256 values are listed in [CHECKSUMS.txt](CHECKSUMS.txt).

---

## Public / private boundary

This repository is an **official public NCore distribution and documentation surface**.

The private NCore Control development repository, internal GDDs, qualification material, build tooling, secrets and other non-public implementation material are not published here.

## Licensing / Licences

NCore Control is proprietary software.

- [NCore Control product license](LICENSE-NCORE-CONTROL.txt)
- [Historical NCore Control 1.0.0 license](licenses/NCore-Control-1.0.0-LICENSE.txt)
- [Public repository rights](LICENSE.md)
- [Official distribution notice](NOTICE.md)
- [Third-party notices](THIRD-PARTY-NOTICES.txt)
- [Copyright](COPYRIGHT.md)

Copyright © 2026 Gosse Nicolas (Boubeur). All Rights Reserved.
