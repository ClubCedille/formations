---
title: "Formation pour les serveurs"
author: Club Cedille
date: Février 2019
output: formations_serveur_cedille
---

# Monalisa (Debian)

## Outils

- LXC : Conteneurs muables
- [Duply](http://duplicity.nongnu.org/) : Système de Backup (duplicity)
- Docker : Conteneurs immuables (Surtout pour monitorage)

# Conteneurs LXC dans Monalisa

## proxy.monalisa.cedille.etsmtl.ca

- nginx
- certbot

## mirroir.cedille.club

- Contient les paquets pour Debian, Ubuntu, Manjaro, Arch & Mx-Linux

# Surveillance

- Prometheus
- Grafana
- Blackbox (requêtes HTTP sur nos sites)
- Node exporter (Info système)
- Le tout sur AWS

# Kipfler

- Proxmox (Gestionnaire de VM)

# Problèmes actuels

#### Reproduction de Monalisa par Ansible est effectuée, mais pas mis en place ni maintenu

#### Problèmes de certificats HTTPS récurrents

#### Maintenance des conteneurs Docker manuelle (MAJ des sites web)

#### Manque de espace disque

#### Monalisa est un point unique d'échec


# Solutions temporaires

### Automatiser:
- mise à jour des sites web (CI/CD)
- création de conteneurs LXC

### Autres tâches
- Stabiliser certbot

# Solutions à long terme

## Appliquer `SRE` (Ingénierie de fiabilité de systèmes)

- C'est quoi ça?

# La vision : Fiabilité de systèmes

_L'ingénieur de la fiabilité c'est quand un ingénieur logiciel se met à désigner les fonctions d'opérations._

![mikefaille](images/socrates.jpg)

