# Bien choisir son PC portable pour le BTS CIEL-IR

**Section TS CIEL-IR – Lycée Louis Rascol**
*Guide mis à jour en septembre 2026. Les prix indiqués sont des ordres de grandeur constatés à cette date : ils bougent vite, vérifiez-les au moment de l'achat.*

---

## Sommaire

1. [Ce dont vous aurez besoin en BTS CIEL-IR](#1-ce-dont-vous-aurez-besoin-en-bts-ciel-ir)
2. [La configuration à viser](#2-la-configuration-à-viser)
3. [Que choisir selon votre budget](#3-que-choisir-selon-votre-budget)
4. [Le reconditionné professionnel : souvent le meilleur choix](#4-le-reconditionné-professionnel--souvent-le-meilleur-choix)
5. [Et un Mac ?](#5-et-un-mac-)
6. [Les pièges à éviter](#6-les-pièges-à-éviter)
7. [Quand et où acheter](#7-quand-et-où-acheter)
8. [Checklist avant de payer](#8-checklist-avant-de-payer)

---

## 1. Ce dont vous aurez besoin en BTS CIEL-IR

Pendant les deux ans, votre PC portable fera tourner en même temps des logiciels gourmands :

| Logiciel | Usage en cours | Ce qu'il consomme |
|---|---|---|
| **Suite JetBrains** (PyCharm, CLion…) | Développement | 2 à 4 Go de RAM par IDE ouvert |
| **Android Studio** + émulateur | Applications mobiles | 4 à 8 Go de RAM, processeur, virtualisation matérielle |
| **VirtualBox** | Serveurs Windows et Linux, pare-feu, maquettes réseau | 1 à 4 Go de RAM **par machine virtuelle** |
| **Docker** | Conteneurs, services web, bases de données | 2 à 6 Go de RAM selon les services |
| **Packet Tracer / Wireshark** | Réseau | Léger |

Un TP classique, c'est par exemple : 2 ou 3 VM + un IDE + un navigateur avec 15 onglets. **Ça dépasse vite 16 Go de RAM.**

> **Le critère n°1 est la mémoire vive (RAM).** Un processeur un peu moins rapide se remarque à peine. Un manque de RAM rend le PC inutilisable en TP.

---

## 2. La configuration à viser

| Composant | Minimum | Recommandé | Pourquoi |
|---|---|---|---|
| **RAM** | 16 Go | **32 Go**, ou 16 Go **extensibles** | Les VM et les IDE consomment beaucoup de RAM |
| **Processeur** | x86 récent, 6 cœurs : AMD Ryzen 5 (7000 ou plus récent), Intel Core i5 (12e gén. ou plus récent), Core Ultra 5 | Ryzen 7 / Core i7 / Core Ultra 7 | Il faut un processeur **x86** pour faire tourner les VM Windows et Linux du cours |
| **Stockage** | SSD NVMe **256 Go** | 512 Go | Les VM Linux consomment peu d'espace (quelques Go). Android Studio et ses images d'émulateur, Docker et les VM Windows en demandent davantage |
| **Écran** | 13" ou 14", Full HD (1920×1080) | 13" à 16", 1920×1200 ou plus, mat, **500 cd/m² (nits)** | Le 13" est très intéressant pour la portabilité. Une luminosité élevée permet de travailler confortablement partout, même près d'une fenêtre |
| **Système** | Windows 11, ou **sans système** | Windows 11, ou sans système pour installer Linux | Un PC vendu sans OS (souvent « FreeDOS ») coûte moins cher : idéal si vous comptez installer Linux. Windows 11 Pro (Hyper-V, Bureau à distance, BitLocker) est utile mais pas indispensable |
| **Ports** | 1 USB-C, 1 USB-A, HDMI | Plus un **port Ethernet RJ45** | En réseau, on se branche souvent en filaire. Sinon, prévoir un adaptateur USB → RJ45 (~15 €) |
| **Autonomie** | 6 h réelles | 8 h ou plus | Pour tenir une journée de cours |
| **Poids** | < 2 kg | < 1,6 kg | Vous le porterez tous les jours |

### Vérifier que la RAM est extensible

Beaucoup de portables récents ont une RAM **soudée** : elle ne pourra jamais être augmentée. Si vous achetez un modèle en 16 Go, choisissez de préférence un modèle avec un **emplacement SO-DIMM libre** ou une RAM remplaçable. Cherchez « RAM soudée » ou « slot SO-DIMM » dans la fiche technique ou sur les forums. Pour un 16 Go non extensible, c'est acceptable, mais il faudra vivre avec pendant deux ans.

---

## 3. Que choisir selon votre budget

Nous recommandons quatre marques : **Lenovo, Dell, HP et Apple** (voir la [section 5](#5-et-un-mac-) pour Apple). Évitez les gammes « premier prix » grand public : charnières fragiles, écrans médiocres, 8 Go soudés. Privilégiez les **gammes professionnelles ou intermédiaires**.

> **Contexte 2026 :** la pénurie mondiale de mémoire (usines réorientées vers l'IA) a fait monter le prix des PC portables de 15 à 20 % depuis le second semestre 2026. Trouver 16 Go en neuf à moins de 600 € est devenu difficile. C'est une raison de plus de regarder le [reconditionné](#4-le-reconditionné-professionnel--souvent-le-meilleur-choix).

### Autour de 500 €

En **neuf**, c'est tendu : vous aurez souvent 16 Go avec quelques compromis (écran, finition, autonomie).

| Marque | Gammes à regarder | Remarques |
|---|---|---|
| Lenovo | IdeaPad Slim 3 / IdeaPad 5 (version **AMD Ryzen** ou **Intel**) | Vérifier le processeur : **pas de Snapdragon** (voir [pièges](#6-les-pièges-à-éviter)) |
| Dell | Dell 15 / Dell 14 (ex-Inspiron) | Beaucoup de versions en 8 Go à ce prix : vérifier la RAM |
| HP | HP 15 / OmniBook 3 | Idem : vérifier RAM et processeur |

**Notre conseil à ce budget : un reconditionné professionnel** (ThinkPad, Latitude, EliteBook) en **16 à 32 Go**. À prix égal, c'est plus solide et mieux équipé. Voir la [section 4](#4-le-reconditionné-professionnel--souvent-le-meilleur-choix).

### Autour de 750 €

C'est le budget le plus raisonnable pour du neuf sans mauvaise surprise.

| Marque | Gammes à regarder | Points forts |
|---|---|---|
| Lenovo | **ThinkPad E14 / E16**, **ThinkBook 14 / 16**, IdeaPad Pro 5 / Slim 5 | ThinkPad E et ThinkBook : clavier excellent, souvent **RJ45** et RAM partiellement extensible |
| Dell | Dell 14 Plus, **Dell Pro 14** (ex-Latitude 3000/5000) | Gamme Pro : solide, bonne garantie |
| HP | **ProBook 4 / ProBook 440–460**, OmniBook 5 | ProBook : gamme pro, souvent RJ45, RAM extensible |

Visez : **Ryzen 5 / Core Ultra 5, 16 Go (extensibles si possible), SSD 256 à 512 Go**.

### Autour de 1000 €

Vous pouvez viser **32 Go** ou un appareil haut de gamme.

| Marque | Gammes à regarder | Points forts |
|---|---|---|
| Lenovo | **ThinkPad T14 / T16**, ThinkPad E14 en 32 Go, ThinkBook 14+ / 16+ | La référence pour durer. T14 AMD : RAM souvent extensible |
| Dell | Dell Pro 14 / Dell Pro 14 Plus (ex-Latitude 5000/7000) | Très bonne qualité de fabrication |
| HP | **EliteBook 6 / EliteBook 8** (ex-EliteBook 640/840) | Finition haut de gamme, bons écrans |
| Dell | **XPS 13 (2026)** : Intel Core 5 320, écran 13,4" 2,5K 120 Hz, SSD 512 Go, 1 kg | Ultraportable très réussi. **Attention** : ~1149 € en 8 Go et **~1299 € en 16 Go** (prix public, sept. 2026), RAM soudée, pas de RJ45. Ne prendre que la version **16 Go**, en promotion ou avec la remise étudiante |
| Apple | MacBook Air M5 16 Go | Voir [section 5](#5-et-un-mac-) : excellent matériel, avec des limites à connaître |

Visez : **Ryzen 7 / Core Ultra 7, 32 Go, SSD 512 Go à 1 To**, ou au moins 16 Go avec possibilité d'extension.

---

## 4. Le reconditionné professionnel : souvent le meilleur choix

Les entreprises renouvellent leurs PC tous les 3 ou 4 ans. Ces machines, **conçues pour durer**, sont reconditionnées et revendues bien moins cher que le neuf.

### Pourquoi c'est intéressant pour vous

- **Robustesse** : clavier, charnières et châssis prévus pour un usage intensif.
- **Réparabilité** : RAM, SSD et batterie souvent remplaçables.
- **Rapport qualité/prix** : un ThinkPad T14 de 2022 en 16 ou 32 Go coûte environ **400 à 600 €**. En neuf, une machine équivalente coûterait le double.
- **Connectique** : RJ45, HDMI et USB-A sont très souvent présents.

### Modèles à rechercher

| Marque | Modèles | Génération minimale conseillée |
|---|---|---|
| Lenovo | ThinkPad **T14**, **T14s**, **X13**, L14, E14 | T14 **Gen 2 (2021)** ou plus récent |
| Dell | **Latitude 5420 / 5430 / 5440**, 7420 / 7430 | Modèles 2021 ou plus récents |
| HP | **EliteBook 840 G8 / G9 / G10**, ProBook 440 G8 ou plus récent | G8 (2021) ou plus récent |

Processeur minimum : **Intel Core i5 de 11e génération** ou **AMD Ryzen 5 PRO 5000**. Évitez les machines plus anciennes : elles sont moins performantes et ont souvent une batterie fatiguée.

### Ce qu'il faut vérifier

- **Grade** : grade A ou « Très bon état ». Évitez les grades C, avec des rayures et un clavier usé.
- **RAM : 16 Go minimum**, idéalement 32 Go. Si la RAM est extensible, vous pouvez acheter en 16 Go et ajouter une barrette plus tard.
- **SSD de 256 Go minimum**, 512 Go si possible.
- **État de la batterie** : demandez sa capacité restante (80 % ou plus). Certains vendeurs remplacent la batterie.
- **Garantie de 12 mois minimum** (certains vendeurs proposent 24 mois).
- **Windows 11 installé avec une licence valide**, sauf si vous comptez installer Linux.
- **Clavier AZERTY français** : certains PC viennent d'autres pays (QWERTY, QWERTZ).

### Où acheter

- **Les sites des marques** : Apple (Produits reconditionnés certifiés), Lenovo, Dell et HP ont tous une boutique de reconditionné/outlet avec garantie constructeur.
- **Back Market** et les **reconditionneurs spécialisés** : garantie d'au moins 12 mois et droit de retour.

> **Attention à eBay et Leboncoin** : entre particuliers, il n'y a souvent **ni garantie ni possibilité de retour**. Même chez un vendeur professionnel sur ces plateformes, vérifiez les conditions de retour et la durée de garantie **avant** de payer. En cas de panne, vous n'aurez aucun recours.

---

## 5. Et un Mac ?

Les Mac récents sont **d'excellentes machines** : très bonne autonomie (15 h ou plus), écran de qualité, silencieux, durables. Ils posent pourtant une contrainte technique à connaître avant d'acheter.

### La contrainte : la puce ARM (Apple Silicon)

Les Mac utilisent des puces **ARM** (M1 à M5), pas des processeurs x86 comme les PC Windows.

- **On ne peut pas faire tourner nativement des VM x86** : ni Windows Server x86, ni les distributions Linux et appliances en x86. L'émulation existe (UTM) mais elle est **très lente**.
- On peut faire tourner des VM **ARM** : Debian, Ubuntu et Windows 11 ARM, avec **VirtualBox 7.1+** ou **UTM**.
- **Pour les VM des TP, votre enseignant fournit une OVA compatible avec les puces M.** Vous pourrez donc suivre les TP. En revanche, vous ne pourrez pas toujours importer directement une VM trouvée sur Internet ou fournie en x86.

### Ce qui fonctionne bien sur Mac

| Logiciel | Sur Mac Apple Silicon |
|---|---|
| Suite JetBrains | Oui, natif, très fluide |
| Android Studio + émulateur | Oui, natif (images ARM), très fluide |
| Docker Desktop | Oui (images ARM, la plupart des images courantes existent) |
| Packet Tracer, Wireshark | Oui |
| VM Linux ARM | Oui (VirtualBox, UTM) |
| VM x86 (Windows Server, appliances) | **Non**, ou très lent en émulation |

### Quel Mac choisir ?

| Modèle | Prix (sept. 2026) | Avis |
|---|---|---|
| **MacBook Air M5 13"** (16 Go / 512 Go) | ~1100 € au prix public, moins en tarif éducation | **Le bon choix Mac**, à la limite haute du budget |
| MacBook Air M2/M3 **16 Go** reconditionné | Variable | Alternative correcte, en vérifiant bien les **16 Go** |

**Sur Mac, la RAM et le SSD ne s'étendent jamais.** Choisissez tout de suite au moins **16 Go et 512 Go**.

> **Bon plan Apple :** le tarif Éducation est disponible toute l'année sur l'Apple Store Éducation. Pendant l'opération de rentrée (jusqu'au 22 octobre 2026), une carte cadeau de 80 à 120 € s'y ajoute. Comparez aussi avec les offres étudiantes des grandes enseignes.

**En résumé :** un Mac est un choix **acceptable** si vous avez le budget pour un modèle 16 Go et que vous acceptez de travailler parfois sur les PC du lycée pour les manipulations qui demandent du x86. Si votre budget est serré, un PC x86 ou un reconditionné pro sera plus simple.

---

## 6. Les pièges à éviter

| Piège | Pourquoi c'est un problème |
|---|---|
| **8 Go de RAM** | Insuffisant dès le premier trimestre. C'est le piège n°1 des offres « pas chères » |
| **PC Windows avec processeur Snapdragon X / « ARM »** | Mêmes limites que le Mac pour les VM x86 (les VM x86 ne fonctionnent pas dans VirtualBox), et certains logiciels ou pilotes ne sont pas compatibles. **Vérifiez que le processeur est un AMD Ryzen ou un Intel Core / Core Ultra** |
| **Stockage eMMC ou SSD de 128 Go** | Trop lent ou trop petit pour les VM et les IDE |
| **Chromebook** | Inadapté : impossible d'installer VirtualBox, les IDE complets et Packet Tracer correctement |
| **Windows en « mode S »** | Bloque l'installation de logiciels hors Microsoft Store. On peut en sortir gratuitement, mais c'est définitif |
| **PC « gamer » d'entrée de gamme** | Lourds, bruyants, 2 à 4 h d'autonomie. La carte graphique ne vous sert à rien ici |
| **Céleron, Pentium, Athlon, Core i3 ancien, Intel N100/N200** | Processeurs trop faibles pour la virtualisation |
| **RAM soudée en 16 Go sur un modèle bas de gamme** | Pas d'évolution possible. Si c'est le cas, préférez directement 32 Go |
| **Vendeur sans garantie** (marketplace, particulier) | Aucun recours en cas de panne |

### Après l'achat : activer la virtualisation

Pour VirtualBox, Docker et l'émulateur Android, la **virtualisation matérielle** doit être activée dans le BIOS/UEFI : **Intel VT-x** ou **AMD-V / SVM**. Elle l'est généralement par défaut. Si une VM refuse de démarrer, c'est la première chose à vérifier. Nous vous montrerons comment faire en cours.

---

## 7. Quand et où acheter

### Quand ?

- **Juillet – août** : promotions de rentrée.
- **Fin novembre** (Black Friday) : souvent les meilleurs prix de l'année.
- **Septembre – octobre** : les prix sont souvent plus élevés, mais le tarif éducation et les offres étudiantes restent actifs.

Si vous n'êtes pas pressé, **attendre le Black Friday** peut faire économiser 10 à 20 %. Les PC du lycée sont disponibles en attendant.

### Où ?

- **Boutiques éducation des constructeurs** : Lenovo, Dell, HP et Apple ont tous un programme étudiant (justificatif de scolarité ou vérification via UNiDAYS / Student Beans).
- **Grandes enseignes et sites marchands** : comparez, les offres étudiantes y sont fréquentes.
- **Reconditionneurs spécialisés** : voir la [section 4](#4-le-reconditionné-professionnel--souvent-le-meilleur-choix).

### Garantie et protection

- La **garantie légale de conformité** est de **2 ans** en neuf et d'**1 an minimum** en reconditionné.
- Les gammes pro (ThinkPad, Dell Pro/Latitude, ProBook/EliteBook) proposent souvent des extensions de garantie **sur site** peu chères. Pour deux ans d'études, c'est une bonne idée.
- Vérifiez si votre **assurance habitation** (ou celle de vos parents) couvre le PC en dehors du domicile (casse, vol).
- **Achetez une housse ou une sacoche rembourrée.** Beaucoup de pannes viennent d'un PC transporté sans protection dans un sac.

---

## 8. Checklist avant de payer

- [ ] Processeur **x86** : AMD Ryzen 5/7 ou Intel Core i5/i7 / Core Ultra 5/7 (**pas de Snapdragon**), ou Mac avec 16 Go en connaissant les limites
- [ ] **16 Go de RAM minimum**, 32 Go idéal, extensible si possible
- [ ] **SSD NVMe de 256 Go minimum** (512 Go si possible)
- [ ] Écran **13" ou plus**, Full HD minimum, 500 cd/m² idéalement
- [ ] Port **RJ45**, ou un adaptateur USB → RJ45 prévu
- [ ] Clavier **AZERTY**
- [ ] Autonomie réelle d'au moins **6 heures** (lire des tests, pas seulement la fiche constructeur)
- [ ] Windows 11 ou **sans système** (pour Linux), **pas en « mode S »**, pas de Chromebook
- [ ] **Garantie** : 2 ans en neuf, 1 an minimum en reconditionné
- [ ] Remise **éducation / étudiante** vérifiée
- [ ] Une **housse de protection**

---

*Une question avant d'acheter ? N'hésitez pas à demander à vos enseignants de la section : envoyez le lien du modèle, nous vous dirons s'il convient.*
