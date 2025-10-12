# Plugins **LunarPhase**
<img src="/assets/images/LunarPhase-Image.png" alt="" style="height: 20%; width:20%;"/> &nbsp; &nbsp;

<img src="/SomfyUnified-Doc/assets/images/LunarPhase-Image.png" alt="LunarPhase logo" style="height: 20%; width:20%;"/> &nbsp; &nbsp;

| Plugin             | Version applicable |
| :----------------: | :----------------: |
| _LunarPhase_       | _1.0.0_            |


_Updated 2025 1003_


## Presentation du plugin LunarPhase
Le plugin **LunarPhase** permet:
- d'afficher en temps réel dans un widget la Lune telle qu'elle apparait à partir du lieu d'observation définit.
- d'avoir accès, à partir des commandes Info aux données techniques complémentaires  (âge, illumination, lever/coucher, ...).


### Rafraichissement des données
L'apparence de la Lune et les données sont mis à jour toutes les minutes.

### Coordonnées GPS (Latitude, Longitude) et fuseau horaire
Afin d'avoir des données représentatives du lieu d'observation, le plugin utilise les coordonnées GPS (Latitude, Longitude) et le fuseau horaire (Timezone) du Jeedom.

Le mécanisme de gestion des coordonnées GPS utilisées par le plugin s'appuie sur la priorité de sélection suivante:
1. Les coordonnées GPS et le fuseau horaire définies dans la page de configuration du plugin (si renseignées par l'utilisateur),
2. sinon les coordonnées GPS et le fuseau horaire définies dans la configuration du Jeedom (si renseignées),
3. sinon les coordonnées GPS par défaut correspondant à Paris (Latitude: 48.8566 - Longitude: 2.3522) utilisées uniquement si aucune autre source valide n’est disponible.


