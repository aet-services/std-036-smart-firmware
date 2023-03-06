# Changelog

Journal des modifications du firmware du SmartVOX®

## 1.4.0 - 2022-10-02

### Corrections

- Correction de l'activation virtuelle des entrées.

### Ajouts

- Ajout de l'option de désactivation du Bluetooth avec réactivation pendant 15 minutes sur apparition d'une tension secteur.

### Modifications

- Amélioration de la vitesse de transmission du Bluetooth.

## 1.3.1 - 2022-10-01

### Corrections

- Correction du timeout de surveillance des équipements du réseau au démarrage de l'appareil.

## 1.3.0 - 2022-07-01

### Ajouts

- Ajout support du module Avior pour la transmission de notifications des alarmes par SMS et Email.
- Ajout de l'option de redémarrage quotidien automatique.

### Modifications

- Gestion dynamique de la périodicité de retransmission des trames d'information sur le réseau radio LoRa afin de respecter le TX Duty Cycle < 1%.

### Corrections

- Correction de la surchage du réseau radio LoRa lorsque des trames non valides sont transmises.

## 1.2.1 - 2021-03-11

### Modifications

- Amélioration du comportement lorsqu'une porteuse radio bloque la fréquence

## 1.2.0 - 2021-03-09

### Ajouts

- Ajout de la configuration du volume des sons système.

### Modifications

- Augmentation de la période d'envoi des trames radio advertising à 60 sec.
- Augmentation du timeout de perte connexion avec un SmartVOX distant à 5 min.
- Amélioration du protocole de transmission radio LoRa en mode LBT selon la norme EN300220-1.

### Corrections

- Correction du redémarrage aléatoire des SmartVOX lors d'une surcharge sur le réseau radio LoRa.

## 1.1.2 - 2020-11-12

### Modifications

- Réinitialisation de la liste des SmartVOX distants après modification d'un paramètre radio.
- Affichage du prompt de la console après appui sur la touche ENTER.

### Corrections

- Correction du type retourné par la commande "remote-device" lorsque l'appareil est non défini.
- Correction du transfert de fichier Ymodem ayant un nom supérieur à 64 caractères.

## 1.1.1 - 2020-10-07

### Modifications

- Amélioration des niveaux d'émissions rayonnés en CEM.

### Corrections

- Correction de l'instabilité du Bluetooth constatée sur une faible partie de la production.

## 1.1.0 - 2020-07-03

### Ajouts

- Ajout de la configuration volatile du volume pour la production.

### Modifications

- Modification de la valeur du volume par défaut à -40 dB.

### Corrections

- Correction du pilotage du Flash en mode visuel avec un déclenchement par état.
- Correction du redémarrage du SmartVOX® lors de plusieurs transferts de sons personnalisés.
- Correction du niveau sonore des sons dans les banques standard et personnalisées.

## 1.0.0 - 2020-06-30

### Ajouts

- Première version du firmware SmartVOX®.
